---
layout: page
title: Home
id: home
permalink: /
---

# Hi there!🌷

👋 My name is Bea and I 've always loved architecture, but recently I've discovered there's so much more to it than what we do at university. That is the reason why I created my digital garden, a public open space for everyone who wants to join me on a beautiful journey of learning and experimenting all about architecture. I hope you find this useful! <3

📚 What I am currently learning about: Masonry and reinforced concrete constructive techniques & how to build a static website

💭 What I am currently thinking about: A parallel between inter-connected notes and inter-connected spaces within a house

<ul>
  {% for note in site.notes %}
    <li>
      <a href="/digitalgarden{{ note.url }}" class="internal-link">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>