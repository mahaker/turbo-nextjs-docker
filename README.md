## Dockerコンテナ作成

```sh
# このリポジトリをclone

pnpm install
docker build -t turbo-next-web .
docker container run -p 3000:3000 --name hoge turbo-next-web

# localhost:3000にアクセス
# apps/webのNext.jsが動いているはずです
```

---

#### プロジェクト生成

```sh
npx create-turbo@latest
```
ref: https://vercel.com/templates/next.js/turborepo-next-basic


