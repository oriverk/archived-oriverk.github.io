---
layout: blog
title: Posting test1
categories: [blog]
tags: [test]
permalink: /blog/:title
---

# {{ page.title }}
<span>{% include svg/tag.svg %}{% for tag in site.tags %}{{ tag[0] }},&nbsp;{% endfor %}&nbsp;Updated at&nbsp;{{ "now" | date: "%Y.%m.%d" }}</span>

I understood Jelyll maybe....
## 可能性
structure of url is
oriverk.github.io/category1/category2/year/month/day/title
,right?

## if so
if i type category in front matter as "category: blog"
what happen?
then, I will do test2.

