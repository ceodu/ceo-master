---
layout: default
title: CEO DU
videos: true
---
<html>
{% include showcase.html %}
</html><script src="https://kit.fontawesome.com/aef02ef4d3.js" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://kit-free.fontawesome.com/releases/latest/css/free-v4-font-face.min.css" media="all">
<div id="what" style="background-color:#0a0a48;
            ">
<div class="container" style="    padding-top: 50px; color:#fff;
    padding-bottom: 50px; text-align: center;">
    <h1 style="font-size: 4rem"> What we do? </h1>

<div class="row first-xs between-sm">
    <div class="col-xs-12 col-sm-4" markdown="1" style="text-align:center">

<div style="font-size: 6rem"><i class="fas fa-search"></i></div>
###  Research and Analysis
We provide high-quality qualitative and quantitative research analysis to early-stage startups. 


  </div>

  <div class="col-xs-12 col-sm-4" markdown="1" style="text-align:center">

<div style="font-size: 6rem"><i class="fas fa-chess"></i></div>
###  Strategy and Product
Strat & product: We focus on what is most important to the client, and how their product will fit in the current marketplace and help achieve their organisational goals.

  </div>

  <div class="col-xs-12 col-sm-4" markdown="1" style="text-align:center">

<div style="font-size: 6rem"><i class="fas fa-users"></i></div>
###  Growth and Marketing
We help early-stage startups gain the traction they always wanted. You can rely on us for results that are exponential.
  </div>

</div>

</div>
</div>

<div style="background-color:#fff; margin-bottom: 3rem;">
  <div class="container" style="padding-top: 50px;
       text-align: center;">
      <h1 style="font-size: 4rem"> Startups We Drink Coffee With</h1>
    <div class="portfolio-images-container">
      <div class="row1">
        <div class="portfolio-images ">
         <a href="https://www.woodsvilleacademy.com/"> <img src="/0.jpg" alt="Woodsville Academy" style="width: 200px"></a>
        </div>
           <div class="portfolio-images ">
          <img src="/upstarter.png" alt="Woodsville Academy" style="width: 200px">
        </div>
        <div class="portfolio-images ">
          <a href="https://aslichatarpatar.com"><img src="/chatarpatar.jpg" alt="Asli Chatar Patar" style="width: 200px"></a>
        </div>
        <div class="portfolio-images ">
          <a href="http://rhvc.in"><img src="/rhv.jpg" alt="Red Herring Ventures" style="width: 200px"></a>
        </div>
     
      </div>

      <!-- <div class="row2">
        <div class="portfolio-images">
          <img src="/0.jpg" alt="Woodsville Academy" style="width: 200px">
        </div>
        <div class="portfolio-images">
          <img src="/0.jpg" alt="Woodsville Academy" style="width: 200px">
        </div>
      </div> -->
   
  </div>
  
</div>






<div class="container">
<hr>
<h1 style="font-size:50px">Must Reads</h1>
{% for post in site.posts %}

{% if post.featured %}
  <div class="posts post-web" >


    <div class="post-title post-title-web" style="margin-bottom: 0rem;"><h1 style="font-weight:600;"><a href="{{ post.url }}">{{ post.title }}</a></h1><h3 style="font-size: 1.8rem;font-weight:300;">~ {{ post.date | date_to_string }}</h3></div>
    {% if post.description %}<p class="post-description post-description-web">{{ post.description }}<br><br><a href="{{ post.url }}"><u >...Read more</u></a></p>{% endif %}

  </div>
  {% endif %}
{% endfor %}
<hr>
</div>
