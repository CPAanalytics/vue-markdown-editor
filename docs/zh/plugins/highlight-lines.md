# Highlight Lines 高亮代码行

github:

<ClientOnly>
  <plugin-highlight-lines-github />
</ClientOnly>

vuepress:

<ClientOnly>
   <plugin-highlight-lines-vuepress />
</ClientOnly>

### Import：

```js
import VueMarkdownEditor from '@cpaanalytics/v-md-editor';
import createHighlightLinesPlugin from '@cpaanalytics/v-md-editor/lib/plugins/highlight-lines/index';

VueMarkdownEditor.use(createHighlightLinesPlugin());
```
