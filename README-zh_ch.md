# diana

![Build Status](https://travis-ci.org/MuYunyun/diana.svg?branch=master) [![codecov](https://codecov.io/gh/MuYunyun/diana/branch/master/graph/badge.svg)](https://codecov.io/gh/MuYunyun/diana) ![LICENSE MIT](https://img.shields.io/npm/l/express.svg)

![](http://oqhtscus0.bkt.clouddn.com/5aa428c1014d75db4d2d331fb2b41334.jpg-muyy)

轻量级工具库（支持 `browser` 和 `node` 环境）。

> [文档地址](http://muyunyun.cn/diana/)

### Install

```bash
yarn add diana || npm install diana --save
```

### Usage

```js
import * as _ from 'diana' // amd
// const _ = require('diana') // common.js
const isEqual = _.equal([1, 2, 3], [1, 2, 3]) // true

// 当然也可以只引用所需的模块
import { isEqual } from 'diana'
```

在浏览器端你也可以直接下载 `min` 目录下的 [diana.js](https://github.com/MuYunyun/diana/blob/master/lib/diana.js) 使用，支持 UMD 通用模块规范。

### Contribute

[how to pr](https://github.com/MuYunyun/diana/blob/master/.github/PULL_REQUEST_TEMPLATE.md)