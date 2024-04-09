# WingUI

[日本語](./README_ja.md)

WingUI is a UI library built for Vue3 and Tailwind.

It complements the Javascript code that Tailwind lacks. The design is simple and modifiable.

## Installation

```bash
npm i @wingui/vue
```

## Components

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
| block | Boolean | false | If true, Tailwind's w-full class is granted. |
| href | String | undefined | When the `href` attribute is set, the `input` is changed to the `a`. |
| disabled | Boolean | false | If true, inactive. |
