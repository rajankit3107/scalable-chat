# @repo/eslint-config

This package contains shared ESLint configurations for the Scalable Chat monorepo.

## Usage

Extend these configs in your apps/packages:

```js
// .eslintrc.js
module.exports = {
  extends: [require.resolve("@repo/eslint-config/next")],
};
```

## Included Configs

- next
- base
- react-internal
