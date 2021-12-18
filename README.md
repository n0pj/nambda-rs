# lambda-rs

lambda で Rust を使用するためのテンプレート

## 使い方

### Setup Template

```
serverless install --url git@github.com:n0pj/lambda-rs.git --name lambda-fn
```

### 確認

```
serverless invoke -f lambda_rs -d '{json:"test"}'
```

### デプロイ

```
serverless deploy
```
