# Tip

<ClientOnly>
  <plugin-tip />
</ClientOnly>

### Import：

```js
import VueMarkdownEditor from '@cpaanalytics/v-md-editor';
import createTipPlugin from '@cpaanalytics/v-md-editor/lib/plugins/tip/index';

VueMarkdownEditor.use(createTipPlugin());
```

### Usage：

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

::: warning
This plugin is already built into the vuePress theme
:::
