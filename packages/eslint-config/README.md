# Shared ESLint configuration for React projects

This [ESLint](https://eslint.org/) configuration deactivates all formatting rules of ESLint and makes sure that [Prettier](https://prettier.io/) is used for code beautifying.

## Integrate into new project

1. Install this package as devDependency

```sh
# yarn
$ yarn add -D @rhumbertgz/eslint-config-react

# npm
$ npm i -D @rhumbertgz/eslint-config-react

# pnpm
$ pnpm add -D @rhumbertgz/eslint-config-react
```

2. Use ESLint config in your project

Create a `.eslintrc.js` file in project root with the following content:

```js
module.exports = {
  extends: ["@rhumbertgz/eslint-config-react"],
};
```
