# Scope: Getting Started

An starter React project instrumented with Scope through GitHub Actions.

This starter project is based on:

- [Create React App](https://github.com/facebook/create-react-app)

## How it works

This project is based on Create React App and includes unit tests run by [Jest](https://jestjs.io/) and end to end tests run by [Cypress](https://www.cypress.io/. It also adds the necessary configuration to run the Javascript Scope Agent.

For more information please refer to the documentation at [https://docs.scope.dev/docs/javascript-installation](https://docs.scope.dev/docs/javascript-installation).

## Running Scope on GitHub Actions

1. Click on `Use this template` button and create the repository in your namespace.
2. Access to [app.scope.dev](https://app.scope.dev).
3. Add/Modify your namespace to include your new repository.
4. Get the API Key for your new repository.
5. Go to your repository on GitHub.
6. Go to Settings -> Secrets.
7. Add your API Key secret.

- Name: `SCOPE_APIKEY`
- Value: `<<your APIKEY>>`

8. Click on `Actions` button and access to the workflow.
9. Click on `Re-run checks`.
