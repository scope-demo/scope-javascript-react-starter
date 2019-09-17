# Scope Javascript Agent React Starter Project

This project is an example of how a react project can be instrumented with the scope agent.

For more information please refer to the documentation at [https://docs.scope.dev/docs/javascript-installation](https://docs.scope.dev/docs/javascript-installation).

## Usage

Checkout the repository:

```bash
git clone git@github.com:scope-demo/scope-javascript-react-starter.git
```

> Alternatively, you may use the `Use this template` button in GitHub.

Change to the repository directory:

```bash
cd scope-javascript-react-starter
```

Install dependencies:

```bash
yarn
```

Set your `SCOPE_API_ENDPOINT` and `SCOPE_APIKEY` in `cypress.env.json` and `.env.test`.

> Please note that these are secrets and should _not_ be part of your repository.

You may also pass these as environment variables when running your tests.

For example:

```bash
SCOPE_API_ENDPOINT=${SCOPE_API_ENDPOINT} SCOPE_APIKEY=${SCOPE_APIKEY} yarn test
```

Run your unit and integration tests:

```bash
yarn test
```

Run your E2E tests:

- Start your application:

```bash
yarn start
```

- Run cypress:

```bash
yarn cypress:run
```
