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