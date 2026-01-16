---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:1%;
    padding-bottom:5px;
    padding-top:5px;
    margin-top:5px;
    margin-bottom:10px;
}
</style>

<!-- <div class="jumbotron">
  <h4>Publications</h4>
  sss
</div> -->


<div class="jumbotron">
<h4>Peer Reviewed Journal Articles</h4>
{% bibliography --query @article %}
</div>

<div class="jumbotron">
<h4>Peer Reviewed Conference Proceedings</h4>
{% bibliography --query @inproceedings %}
</div>

<div class="jumbotron">
<h4>Book Chapters</h4>
{% bibliography --query @inbook %}
</div>

<div class="jumbotron">
<h4>Preprints</h4>
{% bibliography --query @unpublished %}
</div>