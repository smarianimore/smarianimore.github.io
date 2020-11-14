---
title: "Blog"
permalink: /blog/
#classes: single
---

Computer science, engineering, raising kids, dinosaurs, videogames, and whatever else according to my personal and debatable perspective :)

Enjoy :) 

## Latest

{% assign timeframe = 604800 %}
{% assign maxposts = 10 %}
{% assign date_format = site.minima.date_format | default: "%m/%d" %}

<ul class="post-list text-muted list-unstyled">
{% for post in site.posts limit: maxposts %}
  {% assign post_in_seconds = post.last_modified_at | date: "%s" | plus: 0 %}
  {% assign recent_posts = "now" | date: "%s" | minus: timeframe %}
  {% assign post_updated = post.last_modified_at | date: date_format %}
  {% capture post_date %}<small>{{ post.date | date: date_format }}</small>{% endcapture %}

  {% if post_in_seconds > recent_posts %}
  {% capture label_new %}<span class="label label-primary">new</span>{% endcapture %}
    {% if post.last_modified_at > post.date %}
      {% assign label_new = '' %}{% comment %}Clear NEW if modified{% endcomment %}
      {% capture label_updated %}<span class="label label-info">Updated <span class="badge">{{ post_updated }}</span></span>{% endcapture %}
    {% endif %}
  {% endif %}
  <li>
    <em>{{ post_date }}</em>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}</a> {{ label_new }}{{ label_updated }}
    
  </li>
  {% assign post_date = '' %}
  {% assign label_updated = '' %}
{% endfor %}
</ul>

## Tags

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
