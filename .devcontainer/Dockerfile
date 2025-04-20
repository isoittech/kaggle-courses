FROM mcr.microsoft.com/devcontainers/python:1-3.12-bookworm

ARG USERNAME=vscode
ARG USER_UID=1000
ARG USER_GID=$USER_UID

RUN mkdir -p /workspace/kaggle-course

RUN if [ "$USER_GID" != "1000" ] || [ "$USER_UID" != "1000" ]; then \
    groupmod --gid $USER_GID $USERNAME \
    && usermod --uid $USER_UID --gid $USER_GID $USERNAME; \
    fi
RUN chown -R $USER_UID:$USER_GID /home/$USERNAME /workspace;
# RUN echo 'node ALL=(ALL) NOPASSWD: /usr/local/bin/npx' | sudo EDITOR='tee -a' visudo

ENV DEBIAN_FRONTEND=noninteractive

# locales パッケージをインストールし、ロケールを生成
RUN apt-get update \
    && apt-get -y install --no-install-recommends git-lfs \
    && apt-get -y install --no-install-recommends iputils-ping net-tools \
    && apt-get -y install --no-install-recommends nodejs npm \
    && apt-get -y install locales \
    && sed -i -e 's/^# \(ja_JP.UTF-8.*\)/\1/' /etc/locale.gen \
    && locale-gen \
    && update-locale LANG=ja_JP.UTF-8 LANGUAGE=ja_JP:ja LC_ALL=ja_JP.UTF-8 \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*

# 環境変数の設定
ENV LANG=ja_JP.UTF-8
ENV LANGUAGE=ja_JP:ja
ENV LC_ALL=ja_JP.UTF-8
ENV TZ=JST-9
ENV TERM=xterm

# Uncomment to default to non-root user
USER $USER_UID