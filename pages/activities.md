---
layout: page
show_meta: false
title: "Actividades!"
subheadline: "Actividades de la A.M.P.A. del Marcos Frechín"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/activities/"
---
<ul>
    {% for post in site.categories.activities %}
    <li>
        <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
