# `@studion/prettier-config`

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
import baseConfig from "@studion/prettier-config";

export default {
  ...baseConfig,
  trailingComma: "none",
};
```

## TODO 📝

- [ ] Add npm publish script (release-it)
- [ ] Add circleci config
