---
redirect_from: 
  - /lits-of-lists
  - /lol
---
# List of Lists
The following is a list of **lists** on Framewiki. A list is a category of article containing only links to other articles.

<ul>
  {% assign articles = site.pages | where_exp:"i", "i.categories contains 'lists'" %}
  {% for article in articles %}
    <li><a href="{{ article.url | relative_url }}">List of {{ article.title }}</a></li>
  {% endfor %}
</ul>

*This is a dynamic list. All pages in the lists cateogry will appear automatically.*