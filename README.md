# ESCO LP Vercel Ready

このフォルダをGitHubにアップし、VercelでImportすれば公開できます。

## ファイル構成

- `index.html`：LP本体
- `images/`：漫画画像を分離保存
- `vercel.json`：Vercel用の簡易設定

## 送信フォームについて

`index.html` 内の `GAS_WEB_APP_URL` にGoogle Apps ScriptのWebアプリURLを入れると、フォーム送信がGoogleスプレッドシートに保存されます。
