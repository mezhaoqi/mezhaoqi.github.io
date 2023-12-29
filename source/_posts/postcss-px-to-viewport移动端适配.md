---
title: postcss-px-to-viewport移动端适配
date: 2023-12-28 16:36:04
tags:
---
## 安装[postcss-px-to-viewport](https://vant-contrib.gitee.io/vant/#/zh-CN/advanced-usage#viewport-bu-ju)
``` js
npm install postcss-px-to-viewport -D
```

## 配置：`postcss.config.js`

``` js
module.exports = {
  plugins: {
    'postcss-px-to-viewport': {
      // 设备宽度375计算vw的值
      viewportWidth: 375,
    },
  },
};
```