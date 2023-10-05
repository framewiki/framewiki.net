---
meta: true
---
# Framewiki: Contributing
## Guidelines
### Citations
To ensure all content on Framewiki is verifiable, claims should be backed up with citations to a trusted source whenever possible. Community speculation should never be cited as a source, and such citations should be replaced with a [[citation needed]](/framewiki:citation-needed) tag.

To add a citation, insert the following Markdown syntax. It should be inserted after the period at the end of thr sentence it applies to. The number inside the brackets should be the order in which the source was added; it is normal for this to be different from the order it appears on the page. 

```md
[[1]](https://frame.work)
```

### Talk
The official Framework forums' [community guidelines](https://community.frame.work/t/community-guidelines/5) apply in talk spaces on Framewiki.


## Editing Framewiki
To edit Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages.

Be sure to review and follow the above guidelines when editing.

### Editing articles
To update an existing page, click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork, which is where you will make your edits.

### Creating articles
If you are adding a wiki page, click the Add new button at the top right of any page. This should create a new file within the `wiki/` directory, which is where all wiki pages live. Filenames should be all lowercase, ending with `.md`. Titles should be capitalized appropriately.

If the new page should be shown in the menu, ensure you add it via `_includes/sidebar.html`.

### Deploying changes
Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch that Framewiki is automatically built and deployed from. The first time you contribute, an editor, maintainer or admin will need to approve your changes. After that, they will deploy automatically unless they include changes to [protected](/framewiki:protection) parts of the wiki. 
