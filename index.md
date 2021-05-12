---
layout: default
title: "Home"
---

## Introduction

This website will contain articles that explore the programming and reverse engineering of video games. I will assume the reader is familiar with programming, preferably at the lower level.

{% if site.posts.size > 0 %}

## Articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

{% endif %}
