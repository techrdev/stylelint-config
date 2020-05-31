# @techrdev/stylelint-config

> Opinionated Stylelint sharable config for Techr projects.


## Install

```sh
yarn add --dev @techrdev/stylelint-config
```

## Usage

Add a Stylelint config file to your project and extends with our config:

#### `.stylelintrc`
```json
{
  "extends": "@techrdev/stylelint-config"
}
```

## Develop

Run `eslint` for linting the `js` files:

```sh
yarn lint
```

Run tests with `Jest` for checking Styelint rules:

```sh
yarn test
```

## Release

`standard-version` is provided with a `release` command. Just run on `master`:

```sh
yarn release
```

And follow the prompt.


