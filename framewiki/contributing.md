---
meta: true
---
# Framewiki: Contributing
To contribute to Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages. By contributing, you agree to license your contribution under the CC BY-SA 4.0 license. For more information, see [Framewiki: Copyright](/framewiki:copyright).

To edit an existing page, click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork, which is where you will make your edits. Be sure your edits comply with [Framewiki's content standards](/framewiki:guidelines). For information on the basic Markdown syntax, see this [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/).

Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch from which Framewiki is automatically built and deployed. **Your changes will be deployed automatically by the system when you open a pull request,** unless they include changes to [protected](/framewiki:protection) parts of the wiki.

## Advanced Formatting
### Citations
To add a citation, use a numerical footnote. Footnotes in the markdown itself should be numbered in the order in which they were added, even if that is different from the order in which they appear on the page; Jekyll will re-number them on the published site. Wherever possible, include archived copies of sources in the event the orignal becomes unavailable.

In the body of the article:
```md
The quick brown fox hopped over the lazy dog. [^1]
```
Then, add a link to the original source and a copy of it from the Archive.org waybackmachine at the bottom of the page's "References" section:
```md
# References
[^1]: <https://example.com> [Archived]([link to waybackmachine of page](https://web.archive.org/web/20241010024218/http://www.example.com/))
```

### Sidecars
Sidecars are boxes that appear to the right-hand side of pages on Framewiki to provide important information in one place. Information about adding and editing sidecars can be found at [Framewiki: Sidecars](/framewiki:sidecars)

### Notes
Note are boxes that call out important information about a page or it's content, such as that it is a stub or a meta page. Information about adding notes can be found at [Framewiki: Notes](/framewiki:notes)