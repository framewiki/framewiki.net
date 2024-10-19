---
meta: true
---
# Framewiki: Contributing
## Editing Framewiki
To contribute to Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages.

By contributing to Framewiki, you agree to license your contribution under the CC BY-SA 4.0 license. For more information, see [Framewiki: Copyright](/framewiki:copyright).

### How to create an article
If you are adding a wiki page, click the Add new button at the top right of any page. This should create a new file within the `wiki/` directory, which is where all wiki pages live. Filenames should be all lowercase, ending with `.md`. Titles should be capitalized appropriately.

If the new page should be shown in the menu, ensure you add it via `_includes/sidebar.html`.

### How to edit an article
To edit an existing page (or one you've just created), click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork, which is where you will make your edits. For information on the basic Markdown syntax, see this [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/).

#### Citations
To add a citation, use a numerical footnote using this syntax:
```md
The quick brown fox hopped over the lazy dog. [^1]
```
Then, add a link to the original source and a copy of it from the Archive.org waybackmachine as a footnote at the bottom of the page's "References" section using this syntax:
```md
# References
[^1]: <https://example.com> [Archived]([link to waybackmachine of page](https://web.archive.org/web/20241010024218/http://www.example.com/))
```

Footnotes in the markdown itself should be numbered in the order in which they were added, even if that is different from the order in which they appear on the page --- Jekyll will re-number them on the published site. Wherever possible, include archived copies of sources in the event the orignal becomes unavailable.

### How to publish your changes
Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch from which Framewiki is automatically built and deployed. Your changes will be deployed automatically by the system when you open a pull request, unless they include changes to [protected](/framewiki:protection) parts of the wiki.

## Guidelines
### Comment Guidelines
The official Framework forums' [community guidelines](https://community.frame.work/t/community-guidelines/5) apply in talk spaces on Framewiki.

Comments about Framewiki guidelines or technical aspects should be posted to the talk section on this page. Comments on non-meta pages should be specific to the layout or content on that particular page. 

### Verifiability
To ensure all content on Framewiki is verifiable, claims should be backed up with citations to a trusted source whenever possible. Community speculation should never be cited as a source, and such citations should be replaced with a [[citation needed]](/framewiki:citation-needed) tag.

### Creating or Moving Pages
{% include wip.html %}
