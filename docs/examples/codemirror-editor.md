# CodeMirror Editor

<ClientOnly>
  <codemirror-editor />
</ClientOnly>

## Import

```js
import Vue from 'vue';
import VMdEditor from '@cpaanalytics/v-md-editor/lib/codemirror-editor';
import '@cpaanalytics/v-md-editor/lib/style/codemirror-editor.css';
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

Reference:

- [CodeMirror](https://codemirror.net/)
