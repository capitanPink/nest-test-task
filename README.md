## Description

Test application - authorization with bearer

## Installation

```bash
$ npm install
```

## Running the app
### Running the database with docker-compose

```bash
# runs the database instance on localhost:5425
$ docker-compose up -d postgres
```

### Running the application

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
