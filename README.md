openapiにドメインモデルとして扱えるリクエストやレスポンスをcomponentとして定義しておけば(本repoではAuthorやPostなど
以下のコマンドでTypeScriptの型を生成できます。

```shell
npx npx openapi-typescript openapi_v3.json -o openapi.d.ts
```

RedocやSwaggerUIでもEntityとして表示が分かりやすくなった気がするので、時間がある時少しづつ対応していきたいです。