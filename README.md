<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Installation

1. Clone the project.
2. Install the nestjs cli.

```bash
$ npm i -g @nestjs/cli
```

3. Install packages.
```bash
$ yarn install
```

4. Start docker container for DB.
```bash
$ docker compose up -d
```

5. Clone file ```.env.template``` and rename the copy to ```.env```.

6. Fill the env variables defined in ```.env```.

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Execute seed data.

```
GET http://localhost:3000/api/v2/seed
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```