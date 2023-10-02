# `@studion/prettier-config`

[![install size](https://badgen.net/packagephobia/install/@studion/prettier-config)](https://packagephobia.now.sh/result?p=@studion/prettier-config)
[![npm package version](https://badgen.net/npm/v/@studion/prettier-config)](https://npm.im/@studion/prettier-config)
[![github license](https://badgen.net/github/license/ExtensionEngine/prettier-config?service=github)](https://github.com/ExtensionEngine/prettier-config/blob/master/LICENSE)

Studion [Prettier](https://prettier.io) config 💄.

## Installation 💻

- If you are using VSCode, install the following
  [extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- Run the command:

```bash
$ npm i -D prettier @studion/prettier-config
```

- Edit `package.json`:

```jsonc
{
  // ...
  "prettier": "@studion/prettier-config"
}
```

- **OR** create `.prettierrc.js` file if you need to override the base config:

```js
const baseConfig = require("@studion/prettier-config");

module.export = {
  ...baseConfig,
  trailingComma: "none",
};
```
