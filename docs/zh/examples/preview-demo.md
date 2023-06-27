# 预览组件

当你的项目中只需要解析预览 markdown 的时候，可以直接使用此组件。

<ClientOnly>
  <preview-demo />
</ClientOnly>

## 引入

```js
import Vue from 'vue';
import VMdPreview from '@cpaanalytics/v-md-editor/lib/preview';
import '@cpaanalytics/v-md-editor/lib/style/preview.css';
import githubTheme from '@cpaanalytics/v-md-editor/lib/theme/github.js';

VMdPreview.use(githubTheme);

Vue.use(VMdPreview);
```

## 使用

```vue
<template>
  <v-md-preview :text="text"></v-md-preview>
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
