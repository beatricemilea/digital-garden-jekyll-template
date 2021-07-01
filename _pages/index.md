---
layout: page
title: Home
id: home
permalink: /
---

# Hi there!🌷

My name is Bea and I 've always loved architecture, but recently I've discovered there's so much more to it than what we do at university. That is the reason why I created my digital garden, a public open space for everyone who wants to join me on a beautiful journey of learning and experimenting all about architecture. Hope you find this useful! <3

<ul>
  {% for note in site.notes %}
    <li>
      <a href="{{ note.url }}" class="internal-link">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>