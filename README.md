# 逃げ道.xlsx

Viteで作った分岐読み物ゲームです。

## GitHub Pagesで公開する

このプロジェクトはリポジトリ名 `cat` で公開する想定です。
公開URLは次の形になります。

```text
https://<GitHubユーザー名>.github.io/cat/
```

手順:

1. GitHubで `cat` という新規リポジトリを作る
2. このフォルダで下のコマンドを実行する

```powershell
git remote add origin https://github.com/<GitHubユーザー名>/cat.git
git push -u origin main
```

3. GitHubのリポジトリ画面で `Settings` -> `Pages` を開く
4. `Build and deployment` の `Source` を `GitHub Actions` にする
5. `Actions` の `Deploy to GitHub Pages` が完了したら公開URLを開く

## ローカル確認

```powershell
npm install
npm run dev
```

## 公開用ビルド

```powershell
npm run build
```
