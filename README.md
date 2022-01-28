# Entermedia Eslint Config

> ESLint [shareable config](https://github.com/Entermedia-LLC/eslint-config)

[![Support Level](https://img.shields.io/badge/support-active-green.svg)](#support-level)

[@entermedia-llc/eslint-config](https://github.com/Entermedia-LLC/eslint-config) is a shareable configuration package for [eslint](http://eslint.org).

## Installation

1. Install [@entermedia-llc/eslint-config](https://github.com/Entermedia-LLC/eslint-config) as a development dependency of your project:

```sh
npm install @entermedia-llc/eslint-config --save-dev
```

## Available ESLint configs

### @entermedia-llc/eslint-config

The default export contains common rules that are not specific to any framework or environment.

```js
// eslintrc.js
module.exports = {
  extends: ["@entermedia-llc/eslint-config"],
};
```

### @entermedia-llc/eslint-config/next

Extends `@entermedia-llc/eslint-config` adding specific rules to Next.

```js
// eslintrc.js
module.exports = {
  extends: ["@10up/eslint-config/next"],
};
```
