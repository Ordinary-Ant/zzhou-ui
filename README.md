# 简介

## 快速开始

### 安装

```shell
# NPM
$ npm install vue3-zzhou-ui --save

# Yarn
$ yarn add vue3-zzhou-ui

# pnpm
$ pnpm install vue3-zzhou-ui
```

### 完整引入

```ts
import {createApp} from 'vue'
import './style.css'
import App from './App.vue'

import zzhou-ui from 'vue3-zzhou-ui'
import 'vue3-zzhou-ui/style.css'

createApp(App).use(zzhou-ui).mount('#app')
```

## todo

- 迁移组件 测试用例 更新为 vitest
