# Internationalization

::: warning Note
Starting from version 1.4.0, internationalization is supported.
:::

## Introduction

v-md-editor uses Chinese as the default language. If you need to use another language, you can refer to the following approach.

## Language Switching

You can switch the currently used language by using the `use` method. Here's an example:

```js
import enUS from '@cpaanalytics/v-md-editor/lib/lang/en-US';

VueMarkdownEditor.lang.use('en-US', enUS);
```

## Modifying Default Texts

You can modify and extend the texts by using the `add` method. Here's an example:

```js
VueMarkdownEditor.lang.add({
  'zh-CN': {
    h1: {
      toolbar: 'Heading 1',
    },
  },
});
```

## Configuration Files

| Language           | File Name |
| ------------------ | --------- |
| Simplified Chinese | zh-CN     |
| English            | en-US     |
| Korean             | ko-KR     |

You can view all i18n configuration files [here](https://github.com/code-farmer-i/vue-markdown-editor/tree/dev/src/lang).
