---
title: "JAVA"
layout: archive
permalink: categories/JAVA
author_profile: true
sidebar_main: true
---

<!-- 공백이 포함되어 있는 카테고리 이름의 경우 site.categories['a b c'] 이런식으로! -->

***

{% assign posts = site.categories.JAVA %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
