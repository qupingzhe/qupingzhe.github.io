---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title1: 竹杖芒鞋轻胜马，谁怕？
title2: 一蓑烟雨任平生。
---

<div id="myCarousel" class="carousel slide">
    <!-- 轮播（Carousel）指标 -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>   
    <!-- 轮播（Carousel）项目 -->
    <div class="carousel-inner">
        <div class="item active">
            <img src="{{ site.ASSETS }}/images/上古卷轴5.jpg" alt="Third slide">
            <div class="carousel-caption">星空-上古卷轴</div>
        </div>
        <div class="item">
            <img src="{{ site.ASSETS }}/images/华山.jpg" alt="First slide">
            <div class="carousel-caption">山川-华山</div>
        </div>
        <div class="item">
            <img src="{{ site.ASSETS }}/images/沙漠.png" alt="First slide">
            <div class="carousel-caption">沙漠-库布齐</div>
        </div>
    </div>
    <!-- 轮播（Carousel）导航 -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>

