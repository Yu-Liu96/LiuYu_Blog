---
title: 第一次博客
author: LiuYu
date: '2021-09-06'
slug: index.en-us
categories: ['personal']
tags: []
coverImage: /posts/2021-09-06-first-blog/index.en-us_files/BingWallpaper.jpg
thumbnailImagePosition: bottom
thumbnailImage: /posts/2021-09-06-first-blog/index.en-us_files/BingWallpaper.jpg
output:
  blogdown::html_page:
    number_sections: true
    toc: true
description: "This post is about something something."   
---

这是刘11q111 11qq宇11111111写的第一篇博客，作为实验作品。

# 引用

``` r
blogdown::shortcode("alert","success","Note!","Hello.")
```

{{% alert "success" "Note!" "Hello." %}}

我首先在这里引用一 篇我最喜欢的诗词。

> <p class="center">
> 定风波
> </p>
> <p class="center" style="font-size: 20px;">
> 北宋 苏轼
> </p>
> <p class="normal">
> (三月七日沙湖道中遇雨。雨具先去，同行皆狼狈，余独不觉。已而遂晴，故作此词)<br>
> <br>
> 莫听穿林打叶声，何妨吟啸且徐行。竹杖芒鞋轻胜马，谁怕？ 一蓑烟雨1任平生。<br>
> 料峭春风吹酒醒，微冷，山头斜照却相迎。回首向来萧瑟处，归去，也无风雨也无晴。<br>
> </p>

# 代码块

## 类似详细信息1的结果，可以把过长的结果保留，感兴趣的可以自行查看。

<details>

``` r
head(mtcars)
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

</details>

## 插入代码，自动绘图。

``` r
par(mar = c(4, 4, .5, .1))
plot(mpg ~ hp, data = mtcars, pch = 19)
```

<img src="/posts/2021-09-06-first-blog/index.en-us_files/figure-html/unnamed-chunk-3-1.png" width="480" />

## 表格

    {{< toc >}}

<style type="text/css">
.center{
  text-align: center;
  font-family: 'Source Han Serif', 'Songti SC', 'Microsoft YaHei';
  font-style: normal;
  font-size: 30px;
}

.normal{
  font-family: 'Source Han Serif', 'Songti SC', 'Microsoft YaHei';
  font-style: normal;
}

</style>
