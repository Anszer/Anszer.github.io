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

网站本身并不支持下单购买行为，您可以扫描二维码关注微信公众号：不思议の烘焙小屋。再通过公众号购买哦。[GitHub repo](https://github.com/sfreytag/friday-theme) PS：公众号仅支持微信付款。

[The documentation]({{ site.baseurl }}{% link list/projects.md %}) covers the basics of installing and using it, and is an example of how you could write documentation about your own projects.

[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.
第二部分

## 安全资质

不思议的原料取自英国皇家牧场生产的新鲜牛奶，经过89道工序后的黄油、奶酪和奶油奶香味十足，同时生产标准也符合欧盟奶制品规格。不思议的面粉选择王后面粉，总之又贵又好。

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


