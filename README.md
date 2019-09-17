# Scope Javascript Agent React Starter Project

This project is an example of how a react project can be instrumented with the scope agent.

#### Configuration

Checkout the repository:

```bash
git checkout git@github.com:scope-demo/scope-javascript-react-starter.git
```

Go to the repository directory:

```bash
cd scope-javascript-react-starter
```

Install dependencies:

```bash
yarn
```

Set your `SCOPE_API_ENDPOINT` and `SCOPE_APIKEY` in `cypress.env.json` and `.env.test`.

> Please note that these are secrets and should _not_ be part of your repository.

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
