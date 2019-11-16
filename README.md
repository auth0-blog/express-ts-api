# WHATABYTE API: Node, Express, and TypeScript Demo

In this tutorial, you'll build a feature-complete API using Node.js, Express, and TypeScript that lets clients perform data operations on resources that describe a restaurant menu. Using TypeScript with Node.js gives you access to optional static type-checking along with robust tooling for large apps and the latest ECMAScript features.

## Set Up

- Create a `.env` file under the project directory:

```bash
touch .env
```

- Populate `.env` with the following content, replacing the Auth0 variables with the ones from your Auth0 API:

```bash
PORT=7000
AUTH0_DOMAIN=
AUTH0_AUDIENCE=
```

- Install project dependencies:

```bash
npm install
```

- Build the project bundle with webpack Hot-Module Replacement:

```bash
npm run webpack
```

- Run the server:

```bash
npm start
```
