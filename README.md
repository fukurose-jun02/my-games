# My Games

自作のブラウザゲームのまとめサイトです。

- 公開先：https://my-games.fukuchan-app.workers.dev/ （Cloudflare Workers。`main` にpushすると自動で公開）
- `fukurose-jun02.github.io/my-games/` で開いた場合は、上の同じページへ自動で移動します

## ゲーム

| ゲーム | フォルダ |
|---|---|
| 警察犬がにげろ！ | `caterpillar-game/` |
| すみっこつみつみ！ | `sumikko/` |
| お姫様の塔登り | `princess-tower/` |
| キャンディラン | `candy-run/` |
| バイクゲーム | `bike-game/` |

## ファイル

- `index.html`：まとめページ（ゲーム一覧は中の `GAMES` を編集）
- `wrangler.jsonc`：Cloudflare Workers の設定
- `.assetsignore`：サイトに公開しないファイルの一覧
