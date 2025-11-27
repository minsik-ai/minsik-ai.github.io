---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I'm a 2nd year Stanford Masters of Computer Science student.

My areas of interest are representation learning, reinforcement learning, information retrieval and text generation with Large Language Models.

Before coming to Stanford, I have experience in Alexa, AWS AI teams.

Here is my [CV](https://minsik-ai.github.io/files/CV.pdf).

I personally organize a weekly NLP study group for Korean industry professionals and upcoming researchers.
Please feel free to shoot an email if you'd like to join!


# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
