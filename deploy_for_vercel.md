# vercelにデプロイする

## vercel CLI を使ってデプロイする

### install vercel CLI

```zsh
npm i -g vercel
```

バージョンの確認

```zsh
vercel --version
```

### login

```zsh
vercel login
```

### プロジェクトの設定の取得

```zsh
vercel pull --environment=production
```

### build

```zsh
vercel build --prod
```

### deploy

```zsh
vercel deploy --prebuilt --prod
```

## 参考

[Vercel CLI Overview](https://vercel.com/docs/cli)

[Vercel へのビルド＆デプロイをローカル環境から行う](https://techblog.roxx.co.jp/entry/2024/08/19/181743)
