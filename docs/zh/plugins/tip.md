# Tip 提示插件

可以引入 `tip` 插件来支持插入提示信息：

<ClientOnly>
  <plugin-tip />
</ClientOnly>

### 引入：

```js
import VueMarkdownEditor from '@cpaanalytics/v-md-editor';
import createTipPlugin from '@cpaanalytics/v-md-editor/lib/plugins/tip/index';

VueMarkdownEditor.use(createTipPlugin());
```

### 使用：

```vue
<template>
  <v-md-editor v-model="text" left-toolbar="undo redo | tip" height="500px" />
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

::: warning 注意
vuepress 主题已内置此插件
:::
