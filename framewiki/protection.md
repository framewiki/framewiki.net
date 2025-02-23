---
meta: true
protected: true
semiprotected: true
---
# Framewiki: Protection
Articles on Framewiki may be protected by an administrator to prevent vandalism. Pull requests that modify protected pages will not be merged automatically until someone with the appropriate access level approves the changes. Protected pages show a lock icon under the search bar at the top of the page. Fully protected pages have a gold lock with an F on top, while semi protected pages have a grey lock with a user icon on top. Both are seen on this page.

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
Anyone who has submitted changes to Framewiki is considered a contributor. Their changes are automatically published by the system, unless they modify semi- or fully-protected pages or structural/technical files.

## Implementation
Protection is managed via GitHub's `CODEOWNERS` feature and branch protection [rulesets](https://github.com/framewiki/framewiki.net/settings/rules).

### How to Protect an Article

#### Fully-Protected
To fully-protect an article, add the following to `.GITHUB/CODEOWNERS` under the appropriate section.
```
path/to/file @framewiki/admins @framewiki/maintainers @framewiki/editors
```

Then, ensure you add the `protected` note to the article.

#### Semi-Protected
To semi-protect an article, add the following to `.GITHUB/CODEOWNERS` under the appropriate section.
```
path/to/file @framewiki/admins @framewiki/maintainers
```

Then, ensure you add the `semiprotected` note to the article.
