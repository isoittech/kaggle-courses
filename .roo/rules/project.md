# 目的・内容

-   機械学習の能力を向上する
-   https://www.kaggle.com/learn/ の教材で学習する

# ルール

-   なるべく Web 検索を利用して最新の技術情報を使う

# コード品質ルール

1. **関数・コンポーネント定義:**

    - 必ず TypeDoc, PyDoc をつけること
        - 丁寧語（です・ます調）にはしないこと

2. **処理:**

    - 処理にはコメントをつけること
        - 意図・目的を書く

# 備考

-   本プロジェクトのフロントエンド開発では、npm の代わりに pnpm を使っている。
-   本プロジェクトの Python 開発ではパッケージ管理ツールとして、pip の代わりに uv を使っている。
-   下記設定を踏まえてコーディングすること

    ```json: settings.json
        "files.encoding": "utf8",
        "files.eol": "\n",
        "editor.formatOnSave": true,
        "editor.tabSize": 4,
        // インデントを空白文字にする
        "editor.insertSpaces": true,
    ```

    ```json: .prettier.json
    {
        "semi": true,
        "tabWidth": 4,
        "printWidth": 120,
        "trailingComma": "all",
        "bracketSpacing": true,
        "useTabs": false,
        "proseWrap": "always"
    }
    ```
