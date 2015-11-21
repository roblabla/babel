# babel-plugin-transform-async-for-of

Compile ES7 async for...of to ES7 code without async for...of

## Installation

```sh
$ npm install babel-plugin-transform-async-for-of
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["transform-async-for-of"]
}
```

### Via CLI

```sh
$ babel --plugins transform-async-for-of script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["transform-async-for-of"]
});
```
