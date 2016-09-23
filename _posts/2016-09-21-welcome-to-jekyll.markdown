---
layout: post
title:  "255 shades of grey"
date:   2016-09-21 15:08:33 +0100
categories: jekyll update
---



{% for i in (0..255) %}
<div class="strip" style="height:1px;background-color:rgb({{i}},{{i}},{{i}})"></div>
{% endfor %}
