# std-env

[![npm](https://img.shields.io/npm/dm/std-env.svg?style=flat-square)](http://npmjs.com/package/std-env)
[![npm](https://img.shields.io/npm/v/std-env.svg?style=flat-square)](http://npmjs.com/package/std-env)
[![bundlephobia](https://img.shields.io/bundlephobia/min/std-env/latest.svg?style=flat-square)](https://bundlephobia.com/result?p=std-env)

> Detect current Javascript environment

## Installation

```sh
# Using Yarn
yarn add std-env

# Using npm
npm i std-env
```

## Usage

```js
// ESM
import { isWindows } from "std-env";

// CommonJS
const { isCI } = require("std-env");
```

Available exports:

- `env`
- `nodeENV`
- `hasTTY`
- `hasWindow`
- `isCI`
- `isDebug`
- `isDevelopment`
- `isLinux`
- `isMacOS`
- `isMinimal`
- `isProduction`
- `isTest`
- `isWindows`
- `platform`
- `provider`
- `isColorSupported`

You can read more about how each flag works from [./src/flags.ts](./src/flags.ts).

List of well known providers can be found from [./src/providers.ts](./src/providers.ts).

## License

MIT
