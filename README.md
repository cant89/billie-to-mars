# Getting Started

Example Web app made in DDD (frontend) and a very simple backend, with an hardcoded DB, for mocking API.
It shows a list of customers from where you can update some of their informations.

## Front Technologies
- React
- Redux
- Redux Saga
- Typescript
- Material UI (styling)
- Jest (unit tests)
- Express JS (backend)

## Environment

At least Node v10 is required.

## Install and run

### Front-end

```shell
npm i && npm start
```

### Back-end

```shell
cd server && npm i && npm start
```

## Run Tests

```shell
# Run tests once
$ npm run test:once

# Watch tests
$npm run test:watch

# Run tests once with coverage
$npm run test:once:coverage
```

## Production build

```shell
$ npm run build:prod
```

## Stage build

```shell
$ npm run build:stage
```
