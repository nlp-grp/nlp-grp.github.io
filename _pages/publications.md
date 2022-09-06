---
title: "NLP Group @ USF - Publications"
layout: gridlay
excerpt: "NLP Group @ USF -- Publications."
sitemap: false
permalink: /publications/
---


# Selected Publications

For a full list of publications, go to <a href="https://scholar.google.com/citations?hl=en&user=GopCh2QAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar (Neal)</a>, <a href="https://scholar.google.com/citations?hl=en&user=pewRWtIAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar (Licato)</a>, <a href="https://scholar.google.com/citations?hl=en&user=9jFmOukAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar (Gene Kim)</a>, or <a href="https://scholar.google.com/citations?hl=en&user=gFZlotAAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar (Seungbae Kim)</a> or <a href="https://scholar.google.co.in/citations?hl=en&user=ogxlzgcAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar (Ankur Mali)</a>.

<!--
{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>
-->

<!---
## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>
-->

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

