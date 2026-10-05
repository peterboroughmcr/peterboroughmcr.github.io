---
layout: default
title: News Archive
description: Peterborough Model Car Racing Club (PMCR) news archive
---
<p>
{%- assign news_posts = site.categories.news | sort: 'date' | reverse -%}
{%- for post in news_posts -%}
  {{ post.date }} <a href="{{ post.url }}">{{ post.title }}</a><br>
{%- endfor -%}
</p>