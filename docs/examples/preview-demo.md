# Preview Component

<ClientOnly>
  <preview-demo />
</ClientOnly>

## Import

```js
import Vue from 'vue';
import VMdPreview from '@cpaanalytics/v-md-editor/lib/preview';
import '@cpaanalytics/v-md-editor/lib/style/preview.css';
import githubTheme from '@cpaanalytics/v-md-editor/lib/theme/github.js';

VMdPreview.use(githubTheme);

Vue.use(VMdPreview);
```

## Usage

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
