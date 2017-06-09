---
layout: page
title: Summer Speakers Series
link-name: Summer Speakers
permalink: /summer-speakers/
subtitle: June through September, 2017
---

<div class="info-container grid-container">
  <div class="page__intro-text">Design and technology intersect unconventionally to inspire discovery, innovation, and creativity. Explore this space through four exceptional guest speaker engagements during the summer speaker series at IYRS. Organized in coordination with the new Digital Modeling & Fabrication program at IYRS, the speaker series is free and open to the public.</div>
		<!-- <div class="speaker-calendar-link">
				<a class="" href="">View full workshop & speaker calendar
					<img class="triangle-right" src="../img/triangle.png" />
				</a>
		</div> -->
</div>

<div class="speaker-section grid-container ">
  <div class="speaker-section__title"> Our Speakers </div>

<div>
  {% for post in site.categories.speakers reversed %}
  <div class="speaker-section__speakers">
    <img class ="speaker-section__speakers__img" src="{{ post.speaker-img }}"/>
		<p class="speaker-section__speakers__name">{{ post.title }}</p>
		<p class="speaker-section__speakers__date">{{ post.speech-date }}</p>
  </div>
  {% endfor %}
</div>

<div class="grid-container">
  {% for post in site.categories.speakers reversed %}
	<div class="speeches-block">
		<h2 class="speeches-block__speech-title">{{ post.speech-title }}</h2>
    <p class="speeches-block__speaker-name"> {{ post.title }}</p>
		<p class="speeches-block__date">{{ post.speech-date }}</p>
		<p class="speeches-block__desc">{{ post.content }}</p>
		<div class="btn speeches-button"><a href="{{post.event-link}}/">RSVP for this Event</a></div>
	</div>
  {% endfor %}
</div>
