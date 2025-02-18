---
permalink: /events
categories: lists
---
# List of Events
This is a list of **Framework Official Events.**

<ul>
  {% assign articles = site.pages | where_exp:"i", "i.permalink contains '/events/'" | sort: "date" %}
  {% for article in articles %}
    <li><a href="{{ article.url | relative_url }}">{{ article.title }} ({{ article.date | date: "%Y" }})</a></li>
  {% endfor %}
</ul>