# tsconfig

> Shared [TypeScript configuration file](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```bash
npm install --save-dev @joeriess/tsconfig
```

## Usage

To use this configuration you can simply `extend` from it:

```json
{
  "extends": "@joeriess/tsconfig",
  "compilerOptions:": {
    "outDir": "dist"
  }
}
```
