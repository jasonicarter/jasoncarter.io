---
layout: home_new
title: "Home"
date: 
modified:
excerpt:
tags: []
---

<div class="wrapper">
    <header>
        {% if site.owner.avatar %}
        <div class="logo-container">
          <a class="logo" href="{{ page.url }}" style="background-image: url(/images/{{ site.owner.avatar }})"></a>
        </div>
        {% endif %}

        {% if site.owner.name %}
        <div class="author-container"><h1>{{ site.owner.name }}</h1></div>
        {% endif %}

        {% if site.owner.bio %}
        <div class="tagline-container"><p>{{ site.owner.bio }}</p></div>
        {% endif %}
    </header>
    <main>
      {% if site.compass.include_content %}
      <div class="content">
        {% include content.html %}
      </div>
      {% endif %}
    </main>
</div>
