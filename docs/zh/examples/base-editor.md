# 轻量版

编辑器由 textarea 实现，十分轻量。如果对编辑器的没有较高的要求，推荐使用此组件。

<ClientOnly>
  <base-editor />
</ClientOnly>

## 引入

```js
import Vue from 'vue';
import VMdEditor from '@cpaanalytics/v-md-editor';
import '@cpaanalytics/v-md-editor/lib/style/base-editor.css';
import githubTheme from '@cpaanalytics/v-md-editor/lib/theme/github.js';

VMdEditor.use(githubTheme);

Vue.use(VMdEditor);
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
