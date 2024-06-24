___
## Headings and Breaks

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading

Horizontal Rules

Triple dashes:

---

Or Triple underscores:

___

___
## Emphasis

this is _italic_ and so is *this*

this is __bold__ and so is **this**

^^underline^^,  ~~strike through~~

==highlight==  and `inline code`

==*you* **can** ^^combine^^ `too`==

___
## Soft & Hard Line Breaks

Put 2 spaces at the end of a line
to force a line break.
If you simply
hit enter and
don't use 2 spaces
it merges the lines
like this.
You can also force a break <br> anywhere
using the `<br>` tag like we just did

___
## Lists

- need a blank line above to start new list
- valid bullet symbols `*`, `-` or '+'
- nested
    - 4 spaces or 1 tab
    - to indent

1. use *numbers* for ordered
    1. can nest
    3. foo

2. **numbers** can be in order
    1. can also nest

4. but it will fix them if not

- list item with multiple paragraphs.

    anything like this paragraph should be indented by 4 spaces

    and a third

-   you can add blocks too, just indent by 4 spaces

    > :memo: **title**
    >
    > - list under lists
    > - under lists

-   add tables too

    foo | bar
    ----|----
    some|data

___
## Tasks

- [ ] Task Lists `- [ ]`
    - [x] x instead of space
    - [x] will mark it complete
- [ ] work just like lists
    * can can contain indents
    * or anything else a list can

1. Or can be nested under others lists
    - [ ] like this
    - [ ] and this

2. This can help
    - [ ] like this
    - [ ] and this

___
## Links

[simple link](https://www.google.com )

[with optional title](https://www.google.com "Google's Homepage")

point to a [relative file or md](../index.md) or

mail link with emoji [📧](mailto:joshdev@9ci.com) or

click this cloud icon to see the list of icon options

[_cloud_{.icon}](https://material.io/icons/)

or [use an image ![](images/dingus/image-small.png)](images/dingus/image.png)

[Reference-Style Links][some reference id]

put link at bottom of paragraph or page.

you can use numbers or text for [reference-style link definitions][1] or leave it empty and just use the [link text itself]

to [open in new tab](sandbox.md){.new-tab} use `{target=_blank} or {.new-tab}` attributes 

use it on [ref links][new tab]{.new-tab} too

Indenting _reference links_
2 spaces is not required
but a recommended convention

  [some reference id]: https://daringfireball.net/projects/markdown/syntax#link
  [1]: http://reason.com/blog
  [link text itself]: ./images/material.png
  [new tab]: sandbox.md

___
## Images

inline ![](img/friendly_feedback_icon_02.png)
with alt text ![foo](img/friendly_feedback_icon_02.png)
with ref links ![img-small][]
can use [sizing attributes](blocks/#sizing-alignment)

Put `zoomify` in the alt text bracket to enable
clicking to zoom. Try clicking on any of
these images ![zoomify][img-dingus]{.tiny}

![zoomify](img/friendly_feedback_icon_02.png){.center .xsmall}

> :camera: **Figure Title**
> ![zoomify](img/friendly_feedback_icon_02.png){.center .small}

  [img-small]: img/friendly_feedback_icon_02.png
  [img-dingus]: img/friendly_feedback_icon_02.png

___
## Abbreviations

here are some abbr's
HTML and FUBAR

>:bulb: if your editor gets confused by
not having and enclosing * then
just add it to end of abbr def.

---

>:warning: Don't indent these, doesn't seem to work

*[abbr]: Abbreviations
*[def]: Definition
*[HTML]: Hyper Text Markup Language
*[FUBAR]:  You know what it means*

___
## Footnotes

Footnotes[^1] work like reference links
They auto-number like ordered lists[^3]
You can use any
reference id[^text reference]
like ref links they can be
organized at bottom
of paragraph or page.

  [^1]: footnote, click the return icon here to go back ->
  [^3]: the number will not necessarily be what you use
  [^text reference]: text reference
  
___
## Tables

Colons can be used to align columns.
3 dashes min to separate headers.
Outer pipes (|) are optional,
and you don't need to make the
raw Markdown line up prettily.
You can also use inline Markdown.

|  Tables  |      Are      |   Cool    |
| -------- |:-------------:| ---------:|
| col 3 is | right-aligned |     $1600 |
| col 2 is |   centered    |       $12 |
|          |   **Total**   |   **$1612** |

==Table== | **Format** | 👀 _scramble_
--- | --- | ---
*Still* | `renders` | **nicely**
[with links](images/dingus/image-small.png) | images ![zoomify](images/dingus/image-small.png){.tiny} | emojis 🍔
icons _cloud_{.icon} | footnotes[^1] | use `<br>` <br> for multi-line <br> line breaks

___
## Blockquotes

> Blockquotes are handy to callout text.
they are greedy and will keep
grabbing text. The '>' is optional unless trying join
>
paragraphs, tables etc.

a blank line and a new paragraph
or other markdown thing end them

>:bulb:
use a `---` seperator or `<br>`
if you want multiple sepearte block quotes

---

> can have nested
> > blockquotes inside of block quotes
block quotes can also contain any valid markdown

___
## Blocks - admonitions, callouts, sidebars

> :memo: **Memo Admonition**
use blockquotes
with emoji indicators for
admonition memos, callout etc..

---

> :boom:
Title title like above is optional

---

> :bulb: See [the section about blocks](blocks.md#cheatsheet)
for the list of emojis that can be used.

___
## Row divs

<div markdown="1" class="two-column">markdown="1" tells it to process what inside
     <-needs to be a blank line for github to parse

```markdown
|foo | bar |
|----|-----|
|baz | buzz|
```

</div>
<div markdown="1" class="two-column">

|foo | bar |
|----|-----|
|baz | buzz|

</div>   closes the div 

---  this clears the "float" REQUIRED when done

___

<div markdown="1" class="row">

> :bug: **here is another example**
this uses the row class and will make
any blocks, figures, etc equal spaced

---

> :thumbsup: they will be equal sizes
with whatever width is left from image
and as you can see the heights get adjusted to be equal as well

---

![](images/dingus/image.png){.small}

</div>