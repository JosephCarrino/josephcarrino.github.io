---
permalink: /
title: "Welcome to my personal website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Giuseppe Carrino, but everybody calls me Joseph. In this website you will find different resources about me and my work.
I am a PhD at **ENS Lyon** in November 2025, supervised by [Nicolas Brisebarre](https://perso.ens-lyon.fr/nicolas.brisebarre/), [Elisa Riccietti](https://perso.ens-lyon.fr/elisa.riccietti/) and [Theo Mary](https://tmary.perso.lip6.fr/).

About my research
======
During my PhD, I focus on **second-order optimization** methods, especially _Newton's_ algorithm, and floating-point representation, aiming to reduce computational complexity of high-performing optimizers for Machine Learning tasks. Previously, I worked on a framework for the collection, translation and comparative analysis of **online newspaper articles**.

About me
======
Before coming to France, I studied at **University of Bologna**, completing a Bachelor's Degree in **Computer Science** and a Master's Degree in **Artificial Intelligence**. I have also been an intern as **Software Development Engineer** at _Amazon_ Madrid and worked for two months at _NTNU_ in Gjøvik, Norway.

What else?
======
Nothing much! But I love watching movies - especially if old and italian - and playing the guitar, already setting-up a rock band in Lyon if you want to join :grin:.

---
<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}