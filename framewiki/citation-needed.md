---
meta: true
redirect_from:
    - /FW:CITE
---
# Framewiki: Citation Needed
To ensure that all Framewiki content is [verifiable](/framewiki:guidelines#verifiability), Framewiki provides a means for anyone to question an uncited claim. If a statement is not supported by any of the already-linked sources, editors may tag it with [[citation needed]](/framewiki:citation-needed) by inserting the following Markdown:

```md
[[citation needed]](/framewiki:citation-needed)
```

If your work has been tagged as unsupported, attempt to find a source and add it as a citation with a link. If you cannot find an applicable source, leave the citation needed tag or consider removing the statement.

## Pages Needing Citations
This is a list of **pages containing [citation needed] tags**.

<ul>
  {% assign pages = site.pages
  | where_exp:"i", "i.content contains '[citation needed]'"
  | where_exp:"i", "i.title"
  %}
  {% for i_page in pages %}
    {% unless i_page.title contains "Framewiki:" %}
      <li><a href="{{ i_page.url | relative_url }}">{{ i_page.title }}</a></li>
    {% endunless %}
  {% endfor %}
</ul>

*This is a dynamic list. All pages containing at least one citation needed tag will be added automatically.*