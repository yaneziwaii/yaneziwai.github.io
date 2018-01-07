---
layout: archive
title: "学习笔记"
date: 
modified:
excerpt: ""
tags: []
image: 
  feature: notes.gif
  teaser: notes.gif
---

以下是我的学习笔记


<br/>[RWD学习笔记](https://yaneziwaii.github.io/notes/rwd)
<div class="tiles">
{% for post in site.categories.rwd %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 rwd 的列出来-->

<br/>[Infovis学习笔记](https://yaneziwaii.github.io/notes/infovis)
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->