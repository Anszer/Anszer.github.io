---
layout: defaults/page
permalink: about.html
narrow: true
title: More info about 不思议
images:
  - https://images.unsplash.com/photo-1519734014-fec887b3d784?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80
  - https://images.unsplash.com/photo-1499889808931-317a0255c0e9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80
  - https://images.unsplash.com/photo-1486427944299-d1955d23e34d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80
---

## 不思议是什么？

{% include components/intro.md %}
不思议主打造型蛋糕、面包及各类甜品。不思议的独家特色是红茶栗子蛋糕坯，在蛋糕的甜美之上更添一份秋日的温暖。

## 主打甜品


- 蛋糕类
  - 造型蛋糕
  - 纸杯蛋糕
  - 古早蛋糕
  - 芝士乳酪蛋糕
  - 慕斯蛋糕
- 面包类
  - 鸡肉奶油面包
  - 早餐包
  - 软欧
  - 硬欧
- 甜品台
  - 简·爱
  - 傲慢与偏见
  - 罗密欧的复活
- 饼干
  - 三色曲奇
  - 蔓越莓饼干
  - 酥饼
  - 芝麻饼
- 其他
  - 绿豆糕
  - 雪媚娘
  - 冰淇淋
  - 肉松小贝

## Examples

Here's some quick examples of what it can do.
研究项目

### Code Highlighting

{% highlight javascript %}
var modulePattern = (function() {
    // your module code goes here
    var sum = 0 ;

    return {
        add:function() {
            sum = sum + 1;
            return sum;
        },
        reset:function() {
            return sum = 0;
        }
    }
}());
{% endhighlight %}

### Bootstrap Components

Here's a CSS component, it's an alert box with the info color:

<div class="alert alert-info">
    A simple info alert!
</div>

And this is a more sophisticated example, using the JS to include a carousel of images:

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>

The spinner.

<div class="spinner-border text-dark mb-4" role="status">
  <span class="sr-only">Loading...</span>
</div>

### Icons

There's a suite of hundreds of Entypo icons included, here's just a few.

<div class="d-flex align-items-center mb-4">
    <span class="icon grey mr-2">
        {% include entypo/clock.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/cycle.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/chevron-up.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/new-message.svg %}
    </span>
    <span class="icon grey mr-2">
        {% include entypo/shopping-cart.svg %}
    </span>
</div>


