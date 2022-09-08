---
layout: page
title: About
description: 进击的程序员大叔
keywords: 进击的程序员大叔,laining,赖宁
comments: true
menu: 关于
permalink: /about/
---

我是赖宁，一个不那么会总结的程序员大叔。

## 联系

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
