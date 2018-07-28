# diana

![Build Status](https://travis-ci.org/MuYunyun/diana.svg?branch=master) [![codecov](https://codecov.io/gh/MuYunyun/diana/branch/master/graph/badge.svg)](https://codecov.io/gh/MuYunyun/diana) ![LICENSE MIT](https://img.shields.io/npm/l/express.svg)

![](http://oqhtscus0.bkt.clouddn.com/5aa428c1014d75db4d2d331fb2b41334.jpg-muyy)

A lightweight tool library (Support for `browser` and `node` environments)

> [文档地址](http://muyunyun.cn/diana/) :tada:

### Installation

```bash
yarn add diana || npm install diana --save
```

You can also download [diana.js](https://github.com/MuYunyun/diana/blob/master/lib/diana.js) directly in the browser，it support UMD common module specification.

### Usage

```js
import * as _ from 'diana' // amd
// const _ = require('diana') // common.js
const isEqual = _.equal([1, 2, 3], [1, 2, 3]) // true

// ofcource you can import the module you need
import { isEqual } from 'diana'
```

### Contribute

[how to pr](https://github.com/MuYunyun/diana/blob/master/.github/PULL_REQUEST_TEMPLATE.md)