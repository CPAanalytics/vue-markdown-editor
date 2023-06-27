# Base Editor

<ClientOnly>
  <base-editor />
</ClientOnly>

## Import

```js
import Vue from 'vue';
import VMdEditor from '@cpaanalytics/v-md-editor';
import '@cpaanalytics/v-md-editor/lib/style/base-editor.css';
import githubTheme from '@cpaanalytics/v-md-editor/lib/theme/github.js';

VMdEditor.use(githubTheme);

Vue.use(VMdEditor);
```

## Usage

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
