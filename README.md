# @tegor/eslint-config

[![npm](https://img.shields.io/npm/v/@tegor/eslint-config?color=a1b858&label=)](https://npmjs.com/package/@tegor/eslint-config)

## Usage

### Install

```bash
pnpm add -D eslint @tegor/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": "@tegor"
}
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  }
}
```

### Config VS Code auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

## License

[MIT](./LICENSE) License &copy; 2022-PRESENT [dengtuo](https://github.com/fightwithtiger)
