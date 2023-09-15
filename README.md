# CodeMirror Editor

## Таблица
|header|header|header|header|header|
|-|-|-|-|-|
|content|content|content|content|content|
|content|content|content|content|content|

бла-бла-бла

## картинка

![Description](https://fikiwiki.com/uploads/posts/2022-02/1644865303_51-fikiwiki-com-p-skachat-kartinki-khoroshego-kachestva-59.jpg)
<span style='font-size: 12px'>описание картинки</span>

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
