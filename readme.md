# @klauss-m/prettier-config

## Why?

I want to have an easy access to all my configurations.

## Install

You should install it as a dev dependency:

```bash
yarn add prettier @klauss-m/prettier-config -D
```

## Usage

1. add prettier key to your `package.json`

```json
"prettier": "@klauss-m/prettier-config"
```

2. importing from `.prettierrc.json`

```json
"@klauss-m/prettier-config"
```

## Extending

you can extend this config:

```js
module.exports = {
  ...require('@klauss-m/prettier-config'),
  semi: true,
}
```
