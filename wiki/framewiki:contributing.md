# Framewiki: Contributing

## Editing Framewiki
To edit Framewiki, you'll need to have a GitHub account. Framewiki is written in Markdown and deployed via GitHub Pages.

Be sure to review and follow [Framewiki: Guidelines](/framewiki:guidelines) when editing.

### Editing articles
To update an existing page, click the Edit button at the top right of any page to begin editing. If you don't already have one, GitHub will prompt you to create a fork, which is where you will make your edits.

### Creating articles
If you are adding a wiki page, click the Add new button at the top right of any page. This should create a new file within the `wiki/` directory, which is where all wiki pages live. Filenames should be all lowercase, ending with `.md`. Titles should be capitalized appropriately.

If the new page should be shown in the menu, ensure you add it via `_includes/sidebar.html`.

### Deploying changes
Once you've made your changes and committed them, open a Pull Request into `framewiki/framewiki.net:main`, which is the production branch that Framewiki is automatically built and deployed from. The first time you contribute, an editor, maintainer or admin will need to approve your changes. After that, they will deploy automatically unless they include changes to protected parts of the wiki. For more info, see User Access Levels below.

## User Access Levels
Framewiki user access levels are configured via GitHub teams and codeowners.

### @framewiki/admins
Admins have unlimited access to Framewiki. They can:
- Moderate comments/discussions
- Make structural and technical changes to Framewiki
- Push changes directly (without creating a pull request)
- Edit and approve changes to fully- or semi-protected pages

### @framewiki/maintainers
Maintainers are the highest level of non-admin editors. They can: 
- Moderate comments
- Edit and approve changes to fully- or semi-protected pages

### @framewiki/editors
Editors are known, trusted Framewiki editors. They can:
- Edit and approve changes to semi-protected pages

### Contributors
Anyone who has had changes accepted to Framewiki at least once is considered a contributor. Their pull requests with changes are automatically merged, unless they modify semi- or fully-protected pages or structural/technical files.

### First-Time Contributors
The first time someone attempts to contribute, their changes will need to be approved by an editor, maintainer, or admin.