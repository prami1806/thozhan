---
layout: page
show_meta: false
title: "Our Activities"
subheadline: ""
header:
permalink: "/activities/"
---
<ul>
    {% for post in site.categories.activities %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<a class="radius button small" href="https://forms.gle/9n5TKAfcby4JceYN9">Subscribe to our newsletter > </a>