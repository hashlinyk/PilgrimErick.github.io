---
title: Javascript呈现星星评分效果的最简单实现
date: 2017-10-13 15:30:28
tags: Javascript
---

今天群里聊到星星评分实现的需求，突然想起来以前看过此类的一个超简单实现，花了几分钟思考重现了这一小段代码：

```Javascript
    /*
     *  score为分值，范围为0-5 
     */
    function stars(score){
      return "★★★★★☆☆☆☆☆".substr(5 - score, 5);
    }

    stars(3);   //★★★☆☆
```