---
sidecar:
    - title: This is a Sidecar
      text: Sidecars let you summarize important info.
    - html: <br/>
    - image: /assets/giganirav.png
      text: Giganirav is a perfect example image.
    - html: <br/>
    - title_sm: Example Table
      table:
        - label: Framewiki Established
          value: Sept. 13, 2023
        - label: Sidecars added
          value: Oct. 20, 2024
---
# Framewiki: Sidecars
{% include sidecar.html %}
Sidecars are boxes that appear to the right-hand side of pages on Framewiki to provide important information in one place.

Add the following snippet in the location you want the sidecar to appear. In most cases, you should add the sidecar directly below the title. A page can only have one sidecar. Adding this snippet multiple times will show the same sidecar in each location.
```
{% raw  %}{% include sidecar.html %}{% endraw %}
```

## Customizing Sidecar Content
By default, sidecars will show a message directing you to this page. You can change what appears in the sidecar by adding a `sidecar:` tag to the page's front matter, as shown below.
```
---
sidecar:
    - title: This is a section title

    - title_sm: This is a section subtitle

    - image: /assets/giganirav.png

    - text: This is for basic text.

    - html: |
        <span>
            This is for arbetrary HTML.
        </span>

    - table:
        - label: "Year of Release"
          value: "2021"
        - label: "This is a string"
          value: "This is another string"
---
```
Each list item under the sidecar tag represents a section. You can add as many sections as you want. Within a section, you can add multiple types of content. However, you can only add one of each type of content to any section.

Content within a section is ordered by precedence. The order in which the types appear above is the order in which they will appear within a section. To make elements appear in a different order, you can split them into multiple sections.

## Examples
```
---
sidecar:
    # Valid
    - title: Test Title

    # Valid
    - title: Test Title
      text: This is some text that will appear.

    # Valid
    - text: This is for basic text.
      image: /assets/giganirav.png
      table:
        - label: "Year of Release"
          value: "2021"
        - label: "This is a string"
          value: "This is another string"

    # Invalid
    - title: Test Title
      title: This is a second title in the same section.

    # Invalid
    - title-sm: This is a small title.
      image: /assets/giganirav.png
      title-sm: This is a second small title in the same section.
---
```