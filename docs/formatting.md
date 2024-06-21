# Welcome!

## Video Embeds
* https://pypi.org/project/mkdocs-video/
* https://forum.freecodecamp.org/t/youtube-refused-to-connect/245262
![type:video](https://www.youtube.com/embed/uUJShalzWy8)

## Article Embeds
Docs : https://github.com/Aetherinox/mkdocs-link-embeds

```embed
url: https://squidfunk.github.io/mkdocs-material/
```
---

```embed
url:            https://github.com/mkdocs/mkdocs/releases
name:           Github: Download Mkdocs
desc:           MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file. It is designed to be easy to use and can be extended with third-party themes, plugins, and Markdown extensions.
target:         new
```
---

```embed
url:            https://www.youtube.com/watch?v=uUJShalzWy8
name:           Github: Download Mkdocs
desc:           MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file. It is designed to be easy to use and can be extended with third-party themes, plugins, and Markdown extensions.
target:         new
```

> .index is the home page

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
---

**bold text**
*italicized text*
> blockquote lorem impsum
---

### Ordered List 
1. First item
2. Second item
3. Third item
---

### Unordered List
- First item
- Second item
- Third item
---

### Code Block
```python
import coolness

for user in friendly_feedback_users:
    coolness.make_cool(user)
    print(f"Hell yeah {user.name} is cool now!")
```

---

### horizontal rule
---

### link
[title](https://www.example.com)

### image
![alt text](assets/img/favicon.ico)

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Footnote
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID
### My Great Heading {#custom-id}

### Definition List
term
: definition

### Strikethrough
~~The world is flat.~~

### Task List
* [ ] foo
* [x] bar
* [ ] baz
---

### Emoji
That is so funny! :joy:
---

### Highlight
I need to highlight these ==very important words==.
---

### Subscript
H~2~O
---

### Superscript
X^2^
---