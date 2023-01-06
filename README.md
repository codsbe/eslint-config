# @codsbe/eslint-config

This package provides CodsBe's .eslintrc as an extensible shared config.

## Installation

```sh
npm i -D eslint @codsbe/eslint-config eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-import-resolver-typescript eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-simple-import-sort eslint-plugin-unused-imports prettier
```

These rules require the following packages: 
* `eslint`
* `eslint-config-airbnb`
* `eslint-config-airbnb-typescript`
* `eslint-config-prettier`
* `eslint-import-resolver-typescript`
* `eslint-plugin-import`
* `eslint-plugin-jsx-a11y`
* `eslint-plugin-prettier`
* `eslint-plugin-react`
* `eslint-plugin-react-hooks`
* `eslint-plugin-simple-import-sort`
* `eslint-plugin-unused-imports`
* `prettier`

## Usage
```js
// .eslintrc.js
module.exports = {
  extends: ['@codsbe/eslint-config'],
  rules: {
    // override rules here
  },
};
```

## React Native Usage
If you find a rule not related to `react-native`, please add the issue to the gitlab repository
