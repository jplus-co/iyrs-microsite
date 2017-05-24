---
layout: page
title: Summer Speakers Series
link-name: Summer Speakers
permalink: /summer-speakers/
subtitle: June through September, 2017
---


<div class="info-container grid-container">
  <div>View the full workshop and speaker calendar.</div>
  <div>Some text about the speakers and workshops and what the point of them is.</div>
</div>

{% for post in site.categories.speakers %}

<div class="grid-container">
<h1>{{ post.title }}</h1>
</div>


{% endfor %}
