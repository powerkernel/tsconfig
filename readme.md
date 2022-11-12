# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
npm install -D @powerkernel/tsconfig
```

_This config requires TypeScript 4.7 or later._

## Usage

`tsconfig.json`

```json
{
  "extends": "@powerkernel/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
  "extends": "@powerkernel/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2021"
  }
}
```
