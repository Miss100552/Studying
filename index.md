---
layout: post
title: 我的学习笔记
---

# 欢迎来到我的 Studying 仓库

这是我通过 Jekyll 自动生成的第一个页面！

## 我的文章列表
下面会自动列出你 _posts 文件夹里的文章：

<ul>
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
