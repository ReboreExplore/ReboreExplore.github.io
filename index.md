---
layout: default
title: Home
permalink: /    
description: Grad Student @ University of Stuttgart

profile:
  align: right
  image: prof_picture.jpg
---

hi, welcome to my portfolio page. 

I'm Manpa Barman, Grad Student @Universität Stuttgart. I am completing my masters in Information Technology and currently looking for PhD opportunities in AI / Computer Vision, focusing on multimodal and representation learning (vision-language systems).

### Beyond academics 🏃‍♀️ 

I'm an artist at heart. Music, especially Indian classical. I occasionally play the ukelele and like to vibe and groove on Zumba beats. I also enjoy reading fiction. The last book I read last month was "Animal Farm" by George Orwell.

For my long term aspiration of science communication, and currently I am working on improving my writing, teaching and public speaking skills. I have been writing blogs on my Medium on pretty much random topics, but I am currently trying to be more formal and focused on my research area. I like to watch Physics Girl, Veritasium, Computerphile and recently Julia Turc on on YouTube for science communication inspiration.


View my my work so far in my Curriculum Vitae - [CV_April2025]({{ site.baseurl }}/assets/pdf/manpa_resume_2026_Apr.pdfpdf)


## 🗞️ Latest News

{% assign news_items = site.news | sort: 'date' | reverse %}
{% if news_items %}
  <ul>
    {% for item in news_items limit:3 %}
      <li>
        <strong>{{ item.date | date: "%B %d, %Y" }}</strong>: 
        <a href="{{ item.url }}">{{ item.title }}</a>
      </li>
    {% endfor %}
  </ul>
  <a href="{{ '/news/' | relative_url }}">See more news</a>
{% endif %}


## 🎯 Currently

<div class="now-catchy-box">
  <ul>
    <li>🚀 Completed 3/12 books (fiction) as part of my year goal (Will write a quarterly review blog)</li>
    <li>🎶 Vibing to Zumba beats to dance the stress away after work and picking up running as a new hobby </li>
    <li>✍️ Preparing for my master thesis defense presentation
  </ul>
</div>
