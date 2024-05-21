---
title: Hello World
password: pass
abstract: Welcom to my blog, enter password to read.
message: 请输入密码才能查看文章
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

1.Demo 1 - 预设选择第一个【默认】
{% tabs test1 %}  
<!-- tab -->  
**This is Tab 1.**  
<!-- endtab -->  
  
<!-- tab -->  
**This is Tab 2.**  
<!-- endtab -->  
  
<!-- tab -->  This is Tab 3.  <!-- endtab -->  
{% endtabs %}

好好学习

{% tabs Unique name, [index] %} <!-- tab [Tab caption] [@icon] --> Any content (support inline tags too). <!-- endtab --> {% endtabs %}

{% folding 查看图片测试 %}  
  
![](https://cdn.jsdelivr.net/gh/volantis-x/cdn-wallpaper/abstract/41F215B9-261F-48B4-80B5-4E86E165259E.jpeg)  
  
{% endfolding %}  
  
{% folding cyan open, 查看默认打开的折叠框 %}  
  
这是一个默认打开的折叠框。  
  
{% endfolding %}  
  
{% folding green, 查看代码测试 %}  
假装这里有代码块（代码块没法嵌套代码块）  
{% endfolding %}  
  
{% folding yellow, 查看列表测试 %}  
  
- haha  
- hehe  
  
{% endfolding %}  
  
{% folding red, 查看嵌套测试 %}  
  
{% folding blue, 查看嵌套测试2 %}  
  
{% folding 查看嵌套测试3 %}  
  
hahaha <span><img src='https://cdn.jsdelivr.net/gh/volantis-x/cdn-emoji/tieba/%E6%BB%91%E7%A8%BD.png' style='height:24px'></span>  
  
{% endfolding %}  
  
{% endfolding %}  
  
{% endfolding %}

{% tabs test2, 3 %}  
<! -- tab -->  
**This is Tab 1.**  
<! -- endtab -->  
  
<!-- tab -->  
**This is Tab 2.**  
<!-- endtab -->  
  
<!-- tab -->  
**This is Tab 3.**  
<!-- endtab -->  
{% endtabs %}
