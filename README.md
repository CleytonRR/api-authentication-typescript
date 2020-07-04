# API authentication TypeScript

## About :star:

Api for Authentication JWT using TypeScript and TypeORM, project made to studie TypeScript with TypeORM, with routes to create new users and routes to authentication users with token.

## Requirements

This API require:

- [NodeJs](https://nodejs.org/en/)
- [Database relatational](https://www.postgresql.org/)(Mysql, postgres etc)

## Configure :clipboard:

```
$ git clone git@github.com:CleytonRR/api-authentication-typescript.git
```

in root folder create ormconfig.json based on file ormconfigexample.json

**Install dependencies** :clipboard:

```
$ yarn
```

**run migratation** :clipboard:

```
$ yarn typeorm migration:run
```

## Run project :fire:

```
$ yarn dev
```

## technologies :clipboard:

- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeORM](https://typeorm.io/#/)
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [Postgres](https://www.postgresql.org/)
