# @jaredbothwell/tsconfig

Shared TypeScript base configurations.

## Configs

```
base
├── library-base  (emit layer: declaration, declarationMap, sourceMap)
│   ├── cross-platform   (ES2022 lib only, Bundler resolution)
│   ├── node-library     (NodeNext module/resolution)
│   └── react-library    (DOM lib, JSX, Bundler resolution)
├── node             (app)
├── browser          (app)
├── react            (app)
├── next             (app)
└── react-native     (app)
```

## Usage

```json
{
  "extends": "@jaredbothwell/tsconfig/react-native"
}
```

## Install

```sh
npm install -D @jaredbothwell/tsconfig
```
