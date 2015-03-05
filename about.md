---
layout: page
title : About
header : About
group: navigation
---
{% include JB/setup %}

<a href="http://www.awhere.com/registration"><img src="/images/banner-devawhere.jpg" title="source: aWhere.com" /></a>

## Inadequate, inaccurate data has made monitoring and evaluation difficult, if not impossible. 

The aWhere Library contains a growing database of geographically and temporally referenced datasets collected by a wide variety of third parties. The data can be countrywide or sub-regional. It conveys daily, monthly, quarterly, and yearly information across agriculture value chain. Sources of data include large intergovernmental organizations, academic institutions, NGOs, and aWhere clients. Some datasets will be fully available for use under a public access license, while other datasets may require you to register with the original source before using outside the aWhere platform.

After acquiring, verifying, cleaning, and accessing, aWhere provides downloadable agriculture development data from aWhere platform. You can browse relevant metadata here. 

## Browse Data By Tags

<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>

## Browse Data By Categories

<ul class="tag_box inline">
  {% assign categories_list = site.categories %}
  {% include JB/categories_list %}
</ul>
