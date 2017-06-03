---
layout: page
title: Summer Speakers Series
link-name: Summer Speakers
permalink: /summer-speakers/
subtitle: June through September, 2017
---


<div class="info-container grid-container">
  <div class="info-title"> Some text about the speakers and workshops. Some text about the speakers and workshops. 
    Some text about the speakers and workshops and how it relates to the DM&F Program…</div>
		<a class="info-link">
			<span>View full workshop & speaker details</span>
			<i class="arrow-right"></i>
		</a>

</div>

<div class="speaker-section grid-container ">
  <div class="speaker-section-title"> Our Speakers </div>

<div>
  {% for post in site.categories.speakers %}
  <div class="speaker-images">
    <img src="{{ post.speaker-img }}"/>
		<p class="speaker-name-spacing">{{ post.title }}</p>
		<p>{{ post.speech-date }}</p>
  </div>
  {% endfor %}
</div>

<div class="grid-container">
	<div class="speeches-block">
		<h2>Tradition in Contemporary Design</h2>
		<p> June 17, 24 & July 8</p>
		<p> This is a description of the speaker's topic and why you should 
				come to the IYRS to see them speak!</p>
		<div class="btn speeches-button"><a href="studio/">RSVP for this Event</a></div>
	</div>
	<div class="speeches-block">
		<h2>Tradition in Contemporary Design</h2>
		<p> June 17, 24 & July 8</p>
		<p> This is a description of the speaker's topic and why you should 
				come to the IYRS to see them speak!</p>
		<div class="btn speeches-button"><a href="studio/">RSVP for this Event</a></div>
	</div>
	<div class="speeches-block">
		<h2>Tradition in Contemporary Design</h2>
		<p> June 17, 24 & July 8</p>
		<p> This is a description of the speaker's topic and why you should 
				come to the IYRS to see them speak!</p>
		<div class="btn speeches-button"><a href="studio/">Apply Online</a></div>
	</div>
	<div class="speeches-block">
		<h2>Tradition in Contemporary Design</h2>
		<p> June 17, 24 & July 8</p>
		<p> This is a description of the speaker's topic and why you should 
				come to the IYRS to see them speak!</p>
		<div class="btn speeches-button"><a href="studio/">Apply Online</a></div>
	</div>
</div>
