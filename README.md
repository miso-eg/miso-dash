# もふうさラン 🐰🥕

もふもふうさぎが走る、ワンタップのエンドレスランゲーム。
ブラウザだけで動く1ファイル構成（`index.html`）なので、GitHub Pages にそのまま置けます。

## 遊び方

- **タップ / Space / ↑** でジャンプ。空中でもう一度押すと2段ジャンプ
- いがぐり・切り株・ハチに当たるとゲームオーバー
- 高い位置のハチは、ジャンプせずに走ればくぐれる
- 🥕 にんじんは +30点。100点ごとにスピードアップの合図
- ゲームオーバー画面の「𝕏 でポスト」でスコアをシェア

## GitHub Pages で公開する

1. GitHub で新しいリポジトリ（例: `mofuusa-run`、Public）を作る
2. このフォルダを push する

   ```bash
   git remote add origin https://github.com/<ユーザー名>/mofuusa-run.git
   git push -u origin main
   ```

3. リポジトリの **Settings → Pages** で、Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
4. 1〜2分後に `https://<ユーザー名>.github.io/mofuusa-run/` で遊べます

## ローカルで確認

`index.html` をブラウザで開くだけで動きます。
