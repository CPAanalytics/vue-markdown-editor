## Install

```bash
# use npm
npm i @cpaanalytics/v-md-editor -S

# use yarn
yarn add @cpaanalytics/v-md-editor
```

## Quick Start

```js
import Vue from 'vue';
import VueMarkdownEditor from '@cpaanalytics/v-md-editor';
import '@cpaanalytics/v-md-editor/lib/style/base-editor.css';
import vuepressTheme from '@cpaanalytics/v-md-editor/lib/theme/vuepress.js';

VueMarkdownEditor.use(vuepressTheme);

Vue.use(VueMarkdownEditor);
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
