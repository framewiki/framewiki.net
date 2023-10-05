---
meta: true
---
# Framewiki: Contributing

To contribute to Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages.

## Talk/Comment Guidelines
The official Framework forums' [community guidelines](https://community.frame.work/t/community-guidelines/5) apply in talk spaces on Framewiki.

## How To Edit Framewiki

### Updating articles
To update an existing page, click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork, which is where you will make your edits.

### Creating articles
If you are adding a wiki page, click the Add new button at the top right of any page. This should create a new file within the `wiki/` directory, which is where all wiki pages live. Filenames should be all lowercase, ending with `.md`. Titles should be capitalized appropriately.

If the new page should be shown in the menu, ensure you add it via `_includes/sidebar.html`.

### Deploying changes
Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch that Framewiki is automatically built and deployed from. The first time you contribute, an editor, maintainer or admin will need to approve your changes. After that, they will deploy automatically unless they include changes to [protected](/framewiki:protection) parts of the wiki. 

## Citations and Verifiability
To ensure all content on Framewiki is verifiable, claims should be backed up with citations to a trusted source whenever possible. Community speculation should never be cited as a source, and such citations should be replaced with a [[citation needed]](/framewiki:citation-needed) tag.

### How To Add Citations
To add a citation, use a numerical footnote using this syntax:
```md
The quick brown fox hopped over the lazy dog. [^1]
```
Then, add the footnote's content at the bottom of the page's "References" section using this syntax:
```md
# References
[^1]: <https://example.com>
```

Footnotes in the markdown itself should be numbered in the order in which they were added, even if that is different from the order in which they appear on the page --- Jekyll will re-number them on the published site.

## Guidelines for Creating or Moving Pages
{% include wip.html %}