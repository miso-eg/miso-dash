# みそダッシュ 🐰🥕

もふもふうさぎの「みそ」が走る、ワンタップのエンドレスランゲーム。
ブラウザだけで動く1ファイル構成（`index.html`）なので、GitHub Pages にそのまま置けます。

## 遊び方

- **タップ / Space / ↑** でジャンプ。空中でもう一度押すと2段ジャンプ
- いがぐり・切り株・ハチに当たるとゲームオーバー
- ハチは飛んでいる高さをよく見て、とびこえるか、くぐるか見きわめよう
- 🥕 にんじんは +30点。100点ごとにスピードアップの合図
- ゲームオーバー画面の「𝕏 でポスト」でスコアをシェア

## GitHub Pages で公開する

1. GitHub で新しいリポジトリ（例: `miso-dash`、Public）を作る
2. このフォルダを push する

   ```bash
   git remote add origin https://github.com/<ユーザー名>/miso-dash.git
   git push -u origin main
   ```

3. リポジトリの **Settings → Pages** で、Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
4. 1〜2分後に `https://<ユーザー名>.github.io/miso-dash/` で遊べます

## ローカルで確認

`index.html` をブラウザで開くだけで動きます。
