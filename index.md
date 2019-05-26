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
            <img id="picture0-simple" src="{{ site.ASSETS }}/images/上古卷轴5-simple.jpg" alt="Third slide">
            <img id="picture0" src="{{ site.ASSETS }}/images/上古卷轴5.jpg" alt="Third slide">
            <script>$("#picture0").hide()</script>
            <div class="carousel-caption">星空-上古卷轴</div>
        </div>
        <div class="item">
            <img id="picture1-simple" src="{{ site.ASSETS }}/images/华山-simple.jpg" alt="First slide">
            <img id="picture1" src="{{ site.ASSETS }}/images/华山.jpg" alt="First slide">
            <script>$("#picture1").hide()</script>
            <div class="carousel-caption">山川-华山</div>
        </div>
        <div class="item">
            <img id="picture2-simple" src="{{ site.ASSETS }}/images/沙漠-simple.jpg" alt="First slide">
            <img id="picture2" src="{{ site.ASSETS }}/images/沙漠.png" alt="First slide">
            <script>$("#picture2").hide()</script>
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

<script>
for (var i = 0; i < 3; i++) {
    $("#picture" + i).on('load', function(){
        var sId = "#" + $(this).attr('id');
        $(sId + "-simple").hide();
        $(sId).show();
    });
}
                      
for (var i = 0; i < 3; i++) {
    var sId = "#picture" + i;
    if ($(sId).complete || $(sId).height() > 0) {
        $(sId + "-simple").hide();
        $(sId).show();
    }
}
</script>

