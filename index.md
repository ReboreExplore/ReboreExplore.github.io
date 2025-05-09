---
layout: default
title: Home
permalink: /    
description: Grad Student @ University of Stuttgart

profile:
  align: right
  image: prof_picture.jpg
---

hi, welcome to my portfolio page. This is a space for both my professional and hobby projects.

I'm Manpa Barman, Grad Student @Universität Stuttgart. I am pursuing my masters in Information Technology with a focus in deep learning and embedded systems. Of late I am exploring the field of AI and software engineering but yet to figure out my niche. Currently, I am searching 🔍 for a master thesis in the field of foundational deep learning and computer vision.

### Beyond academics 🏃‍♀️ 

I'm an artist at heart. Music, especially Indian classical. I am currently learning music theory and play some ukelele on the go. 

For my long term aspiration of science journalism, I've embarked on a personal journey of self-expression through writing. I've been chronicling my life and experiences on Medium so far, however have been a bit inconsistent oweing to the busy schedule of a grad student. I plan to do more technical blogs in the future.


View my my work so far in my Curriculum Vitae - [CV_April2025]({{ site.baseurl }}/assets/pdf/my_cv.pdf)


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