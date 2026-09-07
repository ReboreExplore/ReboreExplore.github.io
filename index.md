---
layout: default
title: Home
permalink: /    
description: Grad Student @ University of Stuttgart

profile:
  align: right
  image: prof_picture.png
---

hi, welcome to my portfolio page.

I'm Manpa Barman, a Master's graduate in Information Technology from Universität Stuttgart, looking for PhD opportunities in AI / Computer Vision — multimodal and representation learning (vision-language systems).

Beyond research: Indian classical music, ukulele, Zumba, and fiction 📚

<div class="home-grid">
  <div class="home-col">
    <h2>🗞️ Latest News</h2>
    {% assign news_items = site.news | sort: 'date' | reverse %}
    {% if news_items %}
      <ul class="home-news-list">
        {% for item in news_items limit:3 %}
          <li>
            <time>{{ item.date | date: "%b %d, %Y" }}</time>
            <a href="{{ item.url }}">{{ item.title }}</a>
          </li>
        {% endfor %}
      </ul>
      <a class="home-more-link" href="{{ '/news/' | relative_url }}">See more news →</a>
    {% endif %}
  </div>

  <div class="home-col">
    <h2>🎯 Currently</h2>
    <div class="now-catchy-box">
      <ul>
        <li>🚀 Completed 4/12 books (fiction) as part of my year goal</li>
        <li>🎶 Vibing to Zumba beats and picking up running as a new hobby</li>
      </ul>
    </div>

    <h2 class="home-subheading">📖 Reading Queue</h2>
    <div class="now-catchy-box">
      <ul>
        <li>📚 Fiction: <em>The Curious Incident of the Dog in the Night-Time</em> — Mark Haddon</li>
        <li>🎮 Tech: Reinforcement Learning &amp; Unity — for my next Ferienakademie assignment</li>
      </ul>
    </div>
  </div>
</div>
