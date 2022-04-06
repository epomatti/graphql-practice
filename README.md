# graphql-tutorial <img src=".docs/graphql.png" width=80 />

Extensive exercise on GraphQL with Prisma from [How to GraphQL](https://www.howtographql.com/).

```sh
# Add you database entries
cp example.env .env
```

Running it:

```sh
yarn install
yarn dev
```

API should be available at http://localhost:3000/graphql

Testing manually:

```sh
curl -X POST http://localhost:3000/graphql \
  -H "Content-type: application/json" \
  --data-raw '{"query": "query { info }"}'
```
