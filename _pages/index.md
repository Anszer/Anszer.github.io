---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to 不思议の烘焙小屋
---

## 什么是不思议？

{% include components/intro.md %}

[这里是不思议烘焙小屋的招牌主打甜品，欢迎选购哟！]({{ site.baseurl}}{% link _pages/about.md %})

## 如何下单购买

网站本身并不支持下单购买行为，您可以扫描二维码关注微信公众号：不思议の烘焙小屋。再通过公众号购买哦。[公众号二维码](https://pic.rmb.bdstatic.com/242d36bd012f9a5f1c8fd0ef1c0f971f.jpeg@wm_2,t_55m+5a625Y+3L+i0teW3nuaVmeiCsuWPkeW4gw==,fc_ffffff,ff_U2ltSGVp,sz_11,x_7,y_7) PS：公众号仅支持微信付款。

[点击甜品台]({{ site.baseurl }}{% link list/projects.md %}) 包含了目前为止不思议设计过的所有甜品台。

[点击甜品]({{ site.baseurl }}{% link list/posts.html %}) 这是不思议日常营业的各式蛋糕面包和其他一些甜品。


## 安全资质

不思议的原料取自英国皇家牧场生产的新鲜牛奶，经过89道工序后的黄油、奶酪和奶油奶香味十足，同时生产标准也符合欧盟奶制品规格。不思议的面粉选择王后面粉，色素是植物性色素。

同时，不思议当天售卖的甜品都是当天烘焙而成，请各位顾客不用担心食材新鲜度的问题。

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


