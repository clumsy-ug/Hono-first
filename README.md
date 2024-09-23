# Hono-Hands-on

## メモ
- 今回はnpmではなくbunを使用
    - `npm i -g bun`でインストール済み
        - `npm i bun`では`bun run dev`の際にエラーが出てしまったので
    - `bun run dev`
        - 開発サーバー
    - `bun run deploy`
        - https://hono-ja.pages.dev/docs/getting-started/cloudflare-workers
        - Cloudflare Workersのアカウントを持っている場合、 このコマンドだけでCloudflare にデプロイ出来る
        - デプロイしたものはCloudflare WorkersのWorkers & Pagesというセクションを左から選べば見れる
- デプロイ先URL
https://hono-api.rutobe740.workers.dev/
