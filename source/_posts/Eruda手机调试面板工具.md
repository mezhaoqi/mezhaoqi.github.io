---
title: Eruda手机调试面板工具
date: 2023-12-28 15:43:10
tags:
---

[使用方式](https://github.com/liriliri/eruda)

[cdn](https://cdnjs.com/)

```js
   <% if(DEV){ %>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/eruda/3.0.1/eruda.min.js"></script>
    <script>eruda.init()</script>
    <% } %>
```
* 使用 vite-plugin-html 解析模板，默认支持 ejs 模板引擎语法