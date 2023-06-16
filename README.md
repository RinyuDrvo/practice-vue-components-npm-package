# @rinyu-drvo/practice-vue-components-npm-package

このプロジェクトは Vue コンポーネントの npm パッケージ化学習用です

https://www.npmjs.com/package/rinyu-drvo-practice-vue-components-npm-package

## 使い方

```
npm install rinyu-drvo-practice-vue-components-npm-package
```

```vue
<template>
  <dev>
    <my-button>button name</my-button>
  </dev>
</template>

<script>
import MyButton from "@rinyu-drvo/practice-vue-components-npm-package";

export default {
  components: {
    MyButton,
  },
};
</script>
```

## Project setup

```
npm install
```

### build bundle

```
npm run build-bundle
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
