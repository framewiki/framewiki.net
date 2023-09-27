# Framewiki: Protection
Articles on Framewiki may be protected by an administrator to prevent vandalism. Pull requests that modify protected pages will not be merged automatically until someone with the appropriate access level approves the changes, they will be merged automatically.

The admins are currently working on making it so that users with the appropriate access levels don't need review. At this time, it is a GitHub branch protection restriction that we are working around. 

## User Access Levels
Framewiki user access levels are configured via GitHub teams and codeowners.

### @framewiki/admins
Admins have unlimited access to Framewiki. They can:
- Moderate comments/discussions
- Make and approve structural and technical changes to Framewiki
- Push changes directly (without creating a pull request)
- Protect pages
- Approve changes to fully- or semi-protected pages

### @framewiki/maintainers
Maintainers are the highest level of non-admin editors. They can: 
- Moderate comments/discussions
- Approve changes to fully- or semi-protected pages

### @framewiki/editors
Editors are known, trusted Framewiki editors. They can:
- Approve changes to semi-protected pages

### Contributors
Anyone who has had changes accepted to Framewiki at least once is considered a contributor. Their pull requests with changes are automatically merged, unless they modify semi- or fully-protected pages or structural/technical files.

### First-Time Contributors
The first time someone attempts to contribute, their changes will need to be approved by an editor, maintainer, or admin.