---
title: pm2托管
date: 2023-12-28 16:01:30
tags:
---

1、全局按照

``` js
 npm i pm2 -g
```

2、使用

``` js
# pm2 serve 目录 端口  --name 服务名称
pm2 serve ./ 8080 --name my-project
```

3、history路由模式问题，如果有子路径，刷新页面 404

``` js
pm2 serve --spa ./ 8080 --name my-project
```

4、常用命令
``` js
# 查看服务列表
pm2 list
# 删除服务
pm2 delete my-cp-server
```