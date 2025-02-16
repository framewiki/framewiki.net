---
meta: true
---
# Framewiki: Notes
## Adding Notes
To display a note at the top of a page, set the note's name to true in the markdown file's front-matter (between two sets of  dashes at the top of the file). 

Ex:
```md
---
note_name: true
---
```

Alternatively, if it is necessary to display a note inline with content, import it using Jekyll liquid like this:
```md
{{"{% include notes/note_name.html "}}%}
```

The following is a list of the available note names:
- `protected`
- `semiprotected`
- `wip`
- `meta`
- `stub`

## Custom Notes
{% include notes/wip.html %}

## Implementation
Notes at the top of pages are managed by the `notes.html` import, which is hooked into the Jekyll theme via `_config.yml`. Note content and design can be edited by modifying the html file in `_includes` by the same name. 
