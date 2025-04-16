---
layout: link
title: "🧠輸入-閱讀"
subtitle: "與AI一起詠唱"
date: 2025/04/13
author: Hung-Hua Tien

categories: [輸入-閱讀, AI素養, 教育觀點]
tags: [ChatGPT, 自主學習, AI 學習]
courses: input

summary: "教你如何思考 AI 世界中的人與價值。"
image: 
published: true
permalink: /courses/input/
---



## 輸入-閱讀




{% raw %}
{% for post in site.posts %}
  {% if post.course == "ai-literacy" %}

- [{{ post.title }}]({{ post.url }}) <span style="color: gray">({{ post.date | date: "%Y-%m-%d" }})</span>
    {% endif %}
    {% endfor %}
    {% endraw %}
