<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

# Nest.js API with authentication and CRUD data

***

API provides authentication users and CRUD for bookmarks with guards for editing and deletion.
It uses JWT approach with passport-jwt strategy. For validation data: class-validator. Also integrated
***E2E*** tests for all routes.

#### Stack technologies:
- Nest.js Framework with TypeScript
- Postgresql database
- Prisma ORM
- class-validator, class-transformer
- argon2 for hashing passwords
- passport, passport-jwt
- pactumJS as testing tool

## Get started
Create **.env** file based on **.env.example** file!

Launch Docker on computer. In root folder for creation database container in terminal accomplish command:
```bash
$ docker compose up -d
```

## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Prisma studio for visualization and control data through browser interface:

```bash
# Prisma Studio is up on http://localhost:5555
$ npx prisma studio
```

## Test

```bash
# e2e tests
$ yarn run test:e2e
```
