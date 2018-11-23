---
title: hexo搭建博客
date: 2018-11-22 17:52:42
tags: [hexo]
categories: 
- 部署
- hexo 
toc: true
show: true
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).



### 创建一篇新的博客

``` bash
$ hexo new "博客名字"   #hexo new [layout] <title>默认布局为post
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server # 启动服务
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate # 生成静态文件
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy # 发布站点
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

### note

1. 主题下配置的menu菜单栏需要创建对应的页面 ==否则点击菜单栏跳转不到页面出错==

```javascript
# _config.yml menu配置
- page: about # 主页菜单栏名
  directory: about/ # 对应目录
  icon: fa-user # 图标
 hexo new page "对应目录"
```

2. 每篇创建的博客都有fronter-matter，在这里可以个性化文章,使用tags:会在public中生成对应数目的标签文件夹

   categories则会生成对应层级数量的文件夹



***








