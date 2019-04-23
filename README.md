<a href="http://hapijs.com"><img src="https://github.com/hapijs/assets/blob/master/images/family.svg" width="180px" align="right" /></a>

# eslint-config

[![Build Status](https://travis-ci.org/hapijs/eslint-config.svg?branch=master)](https://travis-ci.org/hapijs/eslint-config)

Shareable ESLint config for the hapi ecosystem. To use in your project, add `@hapi/eslint-config` and [`@hapi/eslint-plugin`](https://github.com/hapijs/eslint-plugin) to your `package.json`, then in your ESLint configuration add:

```
{
  "extends": "@hapi/eslint-config"
}
```

**Note:** `@hapi/eslint-plugin` is a plugin containing custom hapi linting rules. It is a peer dependency because of the way ESLint handles shareable configs that include plugins and custom rules (see [eslint/eslint#3458](https://github.com/eslint/eslint/issues/3458) and [eslint/eslint#2518](https://github.com/eslint/eslint/issues/2518) for more background).
