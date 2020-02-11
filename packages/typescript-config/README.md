# @emmafallancy/typescript-config

## Usage

Simply extend the usage with `tsconfig.json`

```
{
  "extends": "./node_modules/@emmafallancy/typescript-config/tsconfig.json",
  "compilerOptions": {
    "target": "es6",
    "module": "commonjs",
    "outDir": "lib",
    "rootDir": "src"
  },
  "include": ["src", "typings"]
}
```
