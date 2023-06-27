## 安装

```bash
# 使用 npm
npm i @cpaanalytics/v-md-editor -S

# 使用yarn
yarn add @cpaanalytics/v-md-editor
```

## 快速开始

```js
import Vue from 'vue';
import VueMarkdownEditor from '@cpaanalytics/v-md-editor';
import '@cpaanalytics/v-md-editor/lib/style/base-editor.css';
import vuepressTheme from '@cpaanalytics/v-md-editor/lib/theme/vuepress.js';

VueMarkdownEditor.use(vuepressTheme);

Vue.use(VueMarkdownEditor);
```

## 使用

```vue
<template>
  <v-md-editor v-model="text" height="400px"></v-md-editor>
</template>

<script>
export default {
  data() {
    return {
      text: '',
    };
  },
};
</script>
```
