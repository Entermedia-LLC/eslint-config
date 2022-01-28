# Entermedia Eslint Config

> ESLint [shareable config](https://github.com/Entermedia-LLC/eslint-config)

[![Support Level](https://img.shields.io/badge/support-active-green.svg)](#support-level)

[@entermedia-llc/eslint-config](https://github.com/Entermedia-LLC/eslint-config) is a shareable configuration package for [eslint](http://eslint.org).

## Installation

1. Install all peer dependencies

```sh
npx install-peerdeps --dev @entermedia-llc/eslint-config
```

2. Install [@entermedia-llc/eslint-config](https://github.com/Entermedia-LLC/eslint-config) as a development dependency of your project:

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
  extends: ["@entermedia-llc/eslint-config/next"],
};
```

## Usage

In order to use this config, choose the one you want and add this configuration to your `package.json`:

```json
{
  "eslintConfig": {
    "extends": "@entermedia-llc/eslint-config"
  }
}
```

Or add a `.eslintrc.js` file to your project root containing:

```js
module.exports = {
  extends: ["@entermedia-llc/eslint-config"],
};
```

## VSCode integration

We recommend turning on VSCode settings to automatically run `eslint --fix` on save.

```json
"editor.codeActionsOnSave": {
   "source.fixAll.eslint": true,
}
```

This will automagically format your code once you save. You don't need VSCode prettier extension enabled or running on save as eslint will automatically run `prettier` for you.

## Support Level

**Active:** Entermedia is actively working on this, and we expect to continue work for the foreseeable future. Bug reports, feature requests, questions, and pull requests are welcome.
