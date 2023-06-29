# Shared Prettier configuration

This shared [Prettier](https://prettier.io/) configuration changes some of the default behavior.

## Integrate into new project

1. Install this package as devDependency

```sh
# yarn
$ yarn add -D @rhumbertgz/prettier-config

# npm
$ npm i -D @rhumbertgz/prettier-config

# pnpm
$ pnpm add -D @rhumbertgz/prettier-config
```

2. Install peer dependencies of this package in your project as devDependencies

Therefore, you can make use of the tool [install-peerdeps](https://github.com/nathanhleung/install-peerdeps):

```sh
# yarn
$ yarn dlx install-peerdeps --dev @rhumbertgz/prettier-config

# npm
$ npx install-peerdeps --dev @rhumbertgz/prettier-config

# pnpm
$ pnpm dlx install-peerdeps --dev @rhumbertgz/prettier-config
```

3. Use Prettier config in your project

Create a `.prettierrc` file in project root with the following content:

```
"@rhumbertgz/prettier-config"
```
