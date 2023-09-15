# Framewiki: Contributing

## The Basics of Contribuitng
To edit Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages. Automations to make editing more wiki-like will be added in the near future.

Be sure to review and follow [Framewiki: Best Practices](/framewiki:best-practices) when editing.

### Editing articles
To update an existing page, click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork. Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch that Framewiki is automatically built and deployed from.

### Creating articles
If you are adding a wiki page, click the Add new button at the top right of any page. This should create a new file within the `wiki/` directory, which is where all wiki pages live. Filenames should be all lowercase, ending with `.md`. Titles should be capitalized appropriately.

If the new page should be show in the menu, ensure you add it via `_includes/sidebar.html`.