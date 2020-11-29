---
layout: page
show_meta: false
title: "Milestones"
subheadline: ""
header:
permalink: "/milestones/"
---
<ul>
    {% for post in site.categories.milestones %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.header.title }}</a></li>
    {% endfor %}
</ul>

<a class="radius button small" href="https://forms.gle/9n5TKAfcby4JceYN9">Subscribe to our newsletter > </a>