# 📚 第1回講義資料：開発環境セットアップガイド

このガイドでは、バイブコーディングを行うための「土台」となるPythonと、最強の相棒「Antigravity」をお使いのパソコンにインストールする手順を解説します。

---

## 🛠️ Step 1: Pythonのインストール

Antigravityを動かすためのエンジンである「Python (パイソン)」をインストールします。

### 🍎 Macをお使いの方

1. **ターミナルを開く**
    * Command + Space キーを押してSpotlight検索を開き、「Terminal」または「ターミナル」と入力してEnterキーを押します。

    > **💡 Homebrew (ホームブリュー) って何？**
    > Macに色々なソフトを簡単にインストールするための「アプリストアのすごい版」みたいな便利ツールです。これがあると、Pythonなどのエンジニア用ツールを一発で入れられるようになります。

2. **Homebrewのインストール確認**
    * 以下のコマンドをコピー＆ペーストしてEnterキーを押します。

        ```bash
        brew --version
        ```

    * 「command not found」と出た場合は、[Homebrew公式サイト](https://brew.sh/index_ja)のコマンドをコピーしてインストールしてください。
3. **Pythonのインストール**
    * 以下のコマンドを実行します。

        ```bash
        brew install python
        ```

4. **確認**
    * 以下のコマンドでバージョンが表示されればOKです。

        ```bash
        python3 --version
        ```

### 🪟 Windowsをお使いの方

1. **インストーラーのダウンロード**
    * [Python公式サイト (python.org)](https://www.python.org/downloads/) にアクセスし、「Download Python 3.x.x」ボタンをクリックします。
2. **インストール実行（⚠️最重要）**
    * ダウンロードしたファイルを開きます。
    * インストール画面の下にある **"Add python.exe to PATH" (パスを通す) に必ずチェックを入れてください**。これ忘れると動きません！
    * 「Install Now」をクリックして完了を待ちます。
3. **確認**
    * スタートメニューから「PowerShell」を開き、以下のコマンドを入力します。
        > **💡 PowerShell と コマンドプロンプト の違いは？**
        > **コマンドプロンプト (黒い画面)** は昔からある古いツール、**PowerShell (青い画面)** はその「進化版」です。
        > PowerShellの方が高機能で、Antigravityのような最新ツールを動かすのに向いているため、今回はこちらを使います。

        ```powershell
        python --version
        ```

---

## 🚀 Step 2: Antigravityのインストール

いよいよ相棒を呼び出します。ここからはターミナル(Mac) / PowerShell(Windows)で行います。

1. **インストールコマンドの実行**
    * 以下のコマンドを入力してEnterキーを押してください。

        ```bash
        pip install antigravity-cli
        ```

        *(※注: 正式な配布パッケージ名に合わせて変更してください。ここでは仮に `antigravity-cli` としています)*

2. **セットアップとログイン**
    * インストール後、以下のコマンドで初期設定を行います。

        ```bash
        antigravity login
        ```

    * ブラウザが開き、認証画面が表示されます。アカウントでログインして連携を許可してください。

3. **動作確認**
    * 以下のコマンドでAntigravityが返事をすれば成功です！

        ```bash
        antigravity hello
        ```

---

🎉 **おめでとうございます！準備完了です！**
これであなたもバイブコーディングを始める準備が整いました。講義でお会いしましょう！
