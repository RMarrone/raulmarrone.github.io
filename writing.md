---
layout: default
title: Writing 
---

<h2>Writing</h2>

<ul class="posts-list">
    {% for post in site.posts %}
        <li>
            <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
