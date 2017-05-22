---
layout: page
title: Summer Speakers
link-name: Summer Speakers
permalink: /summer-speakers/
---

{% for post in site.categories.speakers %}

<div class="grid-container">
<h1>{{ post.title }}</h1>
</div>


{% endfor %}
