---
meta: true
---
# Framewiki: Technical Docs
## Notes
Notes at the top of pages are managed by the `notes.html` import, which is hooked into the Jekyll theme via `_config.yml`. To display a note, set the note's name to true in the markdown file's front-matter (between two sets of  dashes at the top of the file). 

Ex:
```md
note_name: true
```

The following is a list of the available note names:
- `protected`
- `semiprotected`
- `wip`
- `meta`

Note content and design can be edited by modifying the html file in `_includes` by the same name. If it is necessary to display a note inline with content, import it using Jekyll liquid.

## Article Protection
### Fully-Protected
To fully-protect an article, add the following to `.GITHUB/CODEOWNERS` under the appropriate section.
```
path/to/file @framewiki/admins @framewiki/maintainers @framewiki/editors
```

Then, ensure you add the `protected` note to the article via front-matter as described above.

### Semi-Protected
To semi-protect an article, add the following to `.GITHUB/CODEOWNERS` under the appropriate section.
```
path/to/file @framewiki/admins @framewiki/maintainers
```

Then, ensure you add the `semiprotected` note to the article via front-matter as described above.

## Auto-Merge
{% include wip.html %}