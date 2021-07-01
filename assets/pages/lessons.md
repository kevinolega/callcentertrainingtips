---
layout: page
title: LESSONS
permalink: lessons
---
<img src="{{ site.url }}/assets/img/2019-07-Kevin-Gray.jpg" width="150">

We help introverts like you develop confidence the skills to qualify for your dream job.

My name is Kevin Olega.

I'm a project manager for a US-based IT company and HR services firm. 

Before that, I'm a top agent at West Contact Services and a consistent CSAT and TSR awardee at Comcast.

I was also an online English teacher, academic tutor, and sales trainer.

These are my stories on getting a job, building confidence, personal improvement, skills training, and communication skills.

{% include magnet.html %}

{% include popular.html %}

{% include search.html %}

<h3>LATEST LESSONS:</h3>
<p>We've written over seven hundred free lessons to help low-income Filipinos learn skills to qualify for higher-paying jobs.</p> 
<p><a href="https://callcentertrainingtips.com/testimonials/">JOIN HUNDREDS OF FILIPINOS GET HIRED IN A CALL CENTER</a>.</p>  
{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
