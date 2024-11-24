---
title: Thesis
layout: page
blog_index: true
permalink: blog/
thesis:
    - 11/21 Thursday - Day 1
    - 11/22 Friday - Day 2
    - 11/23 Saturday - Day 3
    - 11/24 Sunday - Day 4
    - 11/25 Monday - Day 5
    - 11/26 Tuesday - Day 6
    - 11/27 Wednesday - Day 7
    - 11/28 Thursday - Day 8
    - 11/29 Friday - Day 9
    - 11/30 Saturday - Day 10
    - December
    - 12/1 Sunday - Day 11
    - 12/2 Monday - Day 12
    - 12/3 Tuesday - Day 13
    - 12/4 Wednesday - Day 14
    - 12/5 Thursday - Day 15
    - 12/6 Friday - Day 16
    - 12/7 Saturday - Day 17
    - 12/8 Sunday - Day 18
    - 12/9 Monday - Day 19
    - 12/10 Tuesday - Day 20
    - 12/11 Wednesday - Day 21
    - 12/12 Thursday - Day 22
    - 12/13 Friday - Day 23
    - 12/14 Saturday - Day 24
    - 12/15 Sunday - Day 25
    - 12/16 Monday - Day 26
    - 12/17 Tuesday - Day 27
    - 12/18 Wednesday - Day 28
    - 12/19 Thursday - Day 29
    - 12/20 Friday - Day 30
---

<ul>
    {% for list in page.thesis %}
    <li class="post-item">
        <a class="post-title" href="{{ list }}"><span>{{ list }}</span></a>
    </li>
    {% endfor %}
</ul>

# Writings

<ul>
    {% for post in site.posts %}
    {% unless post.draft == true or post.series %}
    <li class="post-item">
        <a class="post-title" href="{{ post.url }}"><span>{{ post.title }}</span></a>
        <div class="post-date"><i>{{ post.date | date: '%B %-d, %Y' }}</i></div>
    </li>
    {% endunless %}
    {% endfor %}
</ul>

