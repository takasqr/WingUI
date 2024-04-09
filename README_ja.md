# WingUI

[English](./README.md)


WingUI は Vue3 と Tailwind 用に作られた UIライブラリです。Tailwind にはない Javascript のコードを補います。デザインはシンプルで変更可能です。

## インストール

```bash
npm i @wingui/vue
```

## コンポーネント

### Button

```ts
<template>
  <Button>Click me.</Button>
</template>

<script setup lang="ts">
import { Button } from "@wingui/vue"
</script>
```

#### Props

|Name|Type|Default| Description |
|:--|:--|:--|:--|
| block | Boolean | false | true の時 Tailwind の w-full クラスを付与します。 |
| href | String | undefined | href 属性が設定されると、input タグから、a タグに変更されます。 |
| disabled | Boolean | false | true の時、非活性となります。 |
