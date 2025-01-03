---
meta: true
---
# Framewiki: Redirects
Redirects on Framewiki are used to avoid broken links. When a page is moved, a redirect from its previous address should be added. When a page is deleted, a redirect should be added to a related page that includes substantially similar information.

## Shortcuts
Framewiki also uses redirects to create shortcuts to commonly used meta pages. Shortcuts are always capital letters; lowercase is reserved for article names to prevent overlap. A list of these shortcuts is below.

| Shortcut | Full Page                 |
| -------- | ------------------------- |
| FW:CITE  | framewiki:citation-needed |
| FW:GL    | framewiki:guidelines      |

## Usage
To add redirects, insert the following front matter. A page can have an unlimited number of redirect URLs.

```
---
redirect_from:
    - /relative/path
    - /another/relative/path
---
```