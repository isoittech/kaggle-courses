# 目的・内容

-   機械学習の能力を向上する
-   https://www.kaggle.com/learn/ の教材で学習する

# 統計学習計画

## 1. 土台づくり：記述統計の復習／拡張

### 学習内容

-   代表値：平均・中央値・最頻値
-   散布度の指標：分散・標準偏差・四分位範囲
-   分布の形状：歪度・尖度、箱ひげ図

### 自己チェック（この質問に答えられたら OK）

-   データの平均と中央値が大きく食い違う場合、どんな分布形状を疑うか？
-   四分位範囲と標準偏差、それぞれどんな特徴を捉える指標か？
-   箱ひげ図で外れ値と判断する基準は何か？

## 2. 確率論の基礎

### 学習内容

-   確率の公理、事象・標本空間
-   条件付き確率、独立性、ベイズの定理
-   累積分布関数（CDF）の概念

### 自己チェック

-   ある事象 A と B が独立である条件は何か？
-   ベイズの定理を使って「事後確率」を導く手順を説明できるか？
-   CDF と PDF（確率密度関数）の関係を言えるか？

## 3. 確率変数と主要分布

### 学習内容

-   期待値・分散の再確認
-   離散分布：ベルヌーイ、二項、ポアソン、幾何
-   連続分布：一様、正規、指数、ガンマ

### 自己チェック

-   二項分布のパラメータ意味と期待値・分散を導けるか？
-   ポアソン分布が適用される典型例を挙げられるか？
-   正規分布の 68–95–99.7 則を説明できるか？

## 4. 大数の法則と中心極限定理

### 学習内容

-   大数の法則：標本平均の収束
-   中心極限定理：和の正規近似
-   χ² 分布・t 分布へのつながり

### 自己チェック

-   標本平均が母平均に収束する理由を述べられるか？
-   標本サイズが大きいとき、非正規分布でも平均はなぜ正規に近づくか？
-   t 分布と正規分布の違いをパラメータと形状から説明できるか？

## 5. 点推定・区間推定

### 学習内容

-   推定量の性質：不偏性、一致性、効率性
-   最尤推定法（MLE）、モーメント法
-   信頼区間の構成（正規／t 分布基準）

### 自己チェック

-   不偏推定量と有効推定量の違いは何か？
-   MLE の一般的な導出手順を説明できるか？
-   95%信頼区間の解釈を正しく言葉で表現できるか？

## 6. 仮説検定

### 学習内容

-   帰無仮説・対立仮説、第一種・第二種の誤り
-   z 検定、t 検定（片側・両側）
-   カイ二乗検定（適合度／独立性）、分散分析（ANOVA）

### 自己チェック

-   第一種エラーと第二種エラーを混同せずに説明できるか？
-   t 検定の適用条件と手順を整理できるか？
-   ANOVA で「群間変動」と「群内変動」をどう計算するか？

## 7. 回帰分析・モデル化

### 学習内容

-   単回帰分析：推定・決定係数・残差解析
-   重回帰分析：多重共線性、変数選択（AIC/BIC）
-   モデル診断：残差の自己相関・非定常性の検出

### 自己チェック

-   回帰直線の係数を最小二乗法で導出できるか？
-   VIF（分散膨張因子）が高い意味と対処法は何か？
-   残差プロットでモデルの適合性をどう評価するか？

## 8. カテゴリーデータ解析

### 学習内容

-   ロジスティック回帰：オッズ比の解釈
-   クロス集計表の詳細解析（独立性検定、マクネマー検定）

### 自己チェック

-   ロジスティック回帰のロジット関数を説明できるか？
-   オッズ比と相対リスクの違いを言えるか？
-   マクネマー検定はどんなデータに使うか？

## 9. ノンパラメトリック・再標本化

### 学習内容

-   順位検定：マンホイットニー、クラスカル・ワリス
-   ブートストラップ法、ジャックナイフ法

### 自己チェック

-   ノンパラ検定を選ぶ理由は何か？
-   ブートストラップで信頼区間を構築する流れを説明できるか？
-   ジャックナイフとブートストラップの違いは？

## 10. ベイズ統計入門（選択学習）

### 学習内容

-   事前分布・事後分布・事後予測分布
-   MCMC（メトロポリス・ヘイスティングス、ギブスサンプリング）

### 自己チェック

-   ベイズ推定と最尤法の違いを明確に説明できるか？
-   事前分布の選び方が推定結果に与える影響は？
-   ギブスサンプリングの基本ステップを挙げられるか？

## 11. 多変量解析の基礎（発展）

### 学習内容

-   主成分分析（PCA）、因子分析
-   クラスタリング（階層的、k-means）
-   判別分析（LDA/QDA）

### 自己チェック

-   PCA で主成分を選ぶ基準は何か？
-   k-means クラスタリングのアルゴリズムを説明できるか？
-   LDA と QDA の使い分けポイントは？

## 12. 時系列解析・サバイバル解析など（応用）

### 学習内容

-   ARIMA モデル、状態空間モデル
-   コックス比例ハザードモデル

### 自己チェック

-   時系列データの定常性をどう検定するか？
-   ARIMA(p,d,q)モデルの各パラメータの意味は？
-   生存分析でハザード比をどう解釈するか？

## 13. 機械学習との接点（興味に応じて）

### 学習内容

-   決定木、ランダムフォレスト、SVM、ニューラルネットワーク
-   交差検証、正則化（Lasso、Ridge）

### 自己チェック

-   決定木とランダムフォレストの違いを説明できるか？
-   Lasso 回帰のペナルティ項が係数に及ぼす効果は？
-   k‑fold 交差検証の手順を具体的に述べられるか？

---

学習の進め方

-   理論 → 演習 → 実装（R/Python）をセットで繰り返す
-   毎章「自己チェック」の質問に答えながら理解度を確認
-   実データを使って可視化・解析し、数式と結果を結びつけることを重視すること

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

# Jupyter Notebook 編集のルール

1. **ファイルサイズの考慮:**

    - 大きな Jupyter Notebook ファイルは`write_to_file`ツールでは編集できない
    - ファイルを小さな部分に分けて編集する（各セクションごとに`apply_diff`を使用する）

2. **セルタイプの区別:**

    - Python コードのセルでは # が行の先頭に必要
    - マークダウンのセルでは # は行の先頭に入れる必要がない

3. **編集方法:**

    - 編集対象箇所を特定するために`cat`や`grep`などのコマンドを使用する
    - 必要な箇所のみを編集し、不要な部分は変更しない

4. その他
    - 読み取るときは JupyterNotebook の場合多くの行数にまたがるので 300 行ぐらい読む
    - ファイルを新規に作るのは非効率で失敗しやすいので絶対しない。そうなる前にユーザーに質問する
    - 絶対 JupyterNotebook の json 構造が壊れないようにする

# メモ: AI への依頼プロンプト例

- 初回プロンプト
  ```
  @/.roo/rules/project.md に従って統計の学習をしています。あなたは、統計の先生として、対象の学習項目の概念・イメージを私にちゃんと分かるまで説明してください。初学者のための用語解説や例もたくさんお願いします。
  - `# 統計学習計画` の各章にある `自己チェック` に私が答えられるような解説をするようにしてください。
  - JupyterNotebook に教科書のような解説を書いていってください。
  - JupyterNotebook の形式は下記のような感じです。
    ```json
    {
     "cell_type": "markdown",
     "metadata": {},
     "source": [
     ]
    },
    ```
  - です・ます調はやめてください。
  - 既存の同フォルダにある JupyterNotebook の解説粒度が望ましいです。
  - 実世界でどういう役に立つのかも知りたいです。
  - １～５セルずつ承認していきます。一括で書こうとするとファイルが大きくなりすぎ、エラーになるためです。分割して作成する必要があります。
  - Tex は $$ や $ で囲う形式が正しいです。
  
  これから、「3. 確率変数と主要分布」の「xxx」に関する執筆を進めてもらいます。
  対象のファイルは @/super-beginner/ の下に作ります。
  ファイル名は 03-2-kakuritsu-risan-bunpu.ipynb で。
  
  まず、JupyterNotebook のフォーマットを確認したいのでタイトル部分のみ出力してください。
  ```

- 解説追加プロンプト
  ```
  私は統計学の初心者です。
  - 後述の Markdown・コードは統計学に関する JupyterNotebook の Markdown・コードです。
  - 統計学の初心者には難しいため、「である調」で、わかりやすく再構成した例を下記に示してください。
  - わかりやすく、とは、平易な言葉で、例やイメージや言い換えをたくさん使うということです。
  - 実世界でどういう役に立つのかも知りたいです。
  - 「統計学初心者が初めて出会いそうな用語」について解説を入れてください。
  - Tex は $$ や $ で囲う形式が正しいです。
  - 出力内容を「``````」で囲ってください。そうすれば、コピペしやすいです。
  ```

- python 解説プロンプト
  ```py
  上記のようなコード例を提示されたが、「何のために何が言いたいコードなのか」知りたい。コードに詳細なコメント（意図・背景・効果・パラメータ説明）を付けてください。
  変数は、どんな値が設定されうるのか、コメントで例示してください。
  ```