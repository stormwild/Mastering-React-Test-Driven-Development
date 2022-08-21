# Notes

`npm`

```
npm install --save react react-dom
npm install --save-dev @babel/preset-env @babel/preset-react
npm install --save-dev @babel/plugin-transform-runtime
npm install --save @babel/runtime
```

`yarn`

```
yarn add -D react react-dom
yarn add -D @babel/preset-env @babel/preset-react
yarn add -D @babel/plugin-transform-runtime
yarn add @babel/runtime
```

`.babelrc`

```json
{
  "presets": ["@babel/env", "@babel/react"],
  "plugins": ["@babel/transform-runtime"]
}
```

Add TypeScript

```
npm i -D @babel/plugin-transform-typescript
yarn add -D @babel/plugin-transform-typescript
```

[TypeScript-Babel-Starter](https://github.com/microsoft/TypeScript-Babel-Starter)

```
npm i -D typescript @babel/core @babel/cli @babel/plugin-proposal-class-properties @babel/preset-env @babel/preset-typescript
yarn add -D typescript @babel/core @babel/cli @babel/plugin-proposal-class-properties @babel/preset-env @babel/preset-typescript
```

```
tsc --init --declaration --allowSyntheticDefaultImports --target esnext --outDir lib
```