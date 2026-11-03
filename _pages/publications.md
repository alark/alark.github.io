---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
/* Publication buttons: site link blue for PDF, grey for secondary actions */
.btn-pub-pdf{color:#fff;background-color:#127ba3;border:1px solid #127ba3;}
.btn-pub-pdf:hover,.btn-pub-pdf:focus{color:#fff;background-color:#0f6f94;border-color:#0f6f94;}
.btn-pub-link{color:#127ba3;background-color:transparent;border:1px solid #127ba3;}
.btn-pub-link:hover,.btn-pub-link:focus{color:#fff;background-color:#127ba3;}
.btn-pub-bib{color:#555;background-color:transparent;border:1px solid #888;}
.btn-pub-bib:hover,.btn-pub-bib:focus{color:#fff;background-color:#555;border-color:#555;}
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Books 
{% bibliography --query @book %}
</div>


<div class="jumbotron">
### Refereed journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings %}
</div>
