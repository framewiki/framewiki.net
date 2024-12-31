---

# Citations
Framewiki's [verifiability guidelines](/framewiki:guidelines#verifiability) require that all claims be backed up with a citation to a trusted source.

Framewiki uses numerical footnotes for citations. Footnotes in the markdown itself should be numbered in the order in which they were added, even if that is different from the order in which they appear on the page; Jekyll, the static site generator that Framewiki uses, will re-number the footnotes on the published site so they appear in the correct order.

## Syntax
In the body of the article:
```md
The quick brown fox hopped over the lazy dog. [^1]
```
Then, add a link to the original source and a copy of it from the Archive.org waybackmachine at the bottom of the page's "References" section:
```md
# References
[^1]: <https://example.com> [Archived]([link to waybackmachine of page](https://web.archive.org/web/20241010024218/http://www.example.com/))
```

## Archive Links
Wherever possible, include links to archived copies of sources via the Internet Archive's wayback machine in the event the orignal becomes unavailable. To create an archived copy of a page, paste it into <https://web.archive.org/save> and copy the archived URL it gives you. Add it within the footnote as shown above.