# 🪄 補講：世界へデビューする (GitHub & Firebase)

作ったアプリを自分のパソコンの中だけに閉じ込めておくのはもったいない！
今回は「保存」と「公開」の魔法を学び、全世界にあなたの作品を公開します。

---

## 0. この補講のゴール
1. **GitHub**: コードをインターネット上にバックアップする（セーブポイントを作る）。
2. **Firebase Hosting**: 自作のWebサイトやアプリを世界中に公開する。

---

## 1. 座学: その「保存」と「公開」の仕組み

### 🐙 GitHub (ギットハブ) とは？
*   **プログラマーのSNS兼倉庫**です。
*   自分の書いたコードを「リポジトリ」という箱に入れて保存します。
*   「あの時の状態に戻したい！」というタイムマシン機能（バージョン管理）が最強です。

### 🔥 Firebase (ファイアベース) とは？
*   **Googleが提供する最強のアプリ開発プラットフォーム**。
*   今回はその中の「Hosting (ホスティング)」という機能を使います。
*   以前はサーバーを借りて...設定して...と大変でしたが、Firebaseならコマンド一発で「世界公開」できます。

---

## 2. 実技 Part 1: GitHubにコードを保存する

Antigravity (VS Code) のターミナルを使って操作します。

### Step 1: 呪文の準備 (Git初期化)
まずは「ここはGitで管理する場所だよ」と宣言します。

```bash
git init
git add .
git commit -m "First vibe check"
```

*   `git init`: 管理開始の合図。
*   `git add .`: すべてのファイルを「保存候補」にする。
*   `git commit -m "..."`: メッセージ付きでセーブする。

### Step 2: GitHubリポジトリ作成 & 連携
1.  ブラウザで [GitHub](https://github.com/) を開き、右上の「＋」→「New repository」。
2.  Repository name に `my-vibe-app` など好きな名前を入力。
3.  Public (公開) か Private (非公開) を選んで「Create repository」。
4.  出てきた画面の `...or push an existing repository from the command line` の下の3行をコピーして、ターミナルに貼り付け！

```bash
git remote add origin https://github.com/ユーザー名/リポジトリ名.git
git branch -M main
git push -u origin main
```

これであなたのコードがクラウドに保存されました！

---

## 3. 実技 Part 2: Firebaseで世界公開

### Step 1: 道具のインストール
Firebaseを操るためのツール (`firebase-tools`) を入れます。

```bash
npm install -g firebase-tools
```

### Step 2: ログイン & 初期設定
Googleアカウントで認証します。

```bash
firebase login
```
※ブラウザが開くので、許可してください。

次に、プロジェクトの初期設定をします。

```bash
firebase init hosting
```
ここから少し対話モードになります：
1.  **Are you ready to proceed?**: `y` (Yes)
2.  **Please select an option**: `Create a new project` (新規作成)
3.  **Unique project ID**: `vibe-app-自分の名前` (世界で1つだけのIDにする必要あり)
4.  **What do you want to use as your public directory?**:
    *   HTMLサイトの場合: `.` (現在のフォルダ) または `public`
    *   React (Vite) の場合: `dist`
5.  **Configure as a single-page app?**: `y` (ReactならYes)
6.  **Set up automatic builds and deploys with GitHub?**: `n` (今回はNo)

### Step 3: デプロイ (発射！)
Reactの場合は、まずビルド（翻訳）が必要です。

```bash
npm run build
```

準備ができたら、いよいよ公開です。

```bash
firebase deploy
```

成功すると `Hosting URL: https://...` と表示されます。
このURLをクリックすれば、あなたのアプリが世界中から見られるようになっています！🎉
