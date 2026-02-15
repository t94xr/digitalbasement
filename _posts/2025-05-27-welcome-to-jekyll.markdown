---
layout: post
title:  "Markdown Showcase!"
date:   2025-05-27 18:07:15 +1200
tags: jekyll update
toc: true
---

This post demonstrates the most common markdown syntax.

## Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

Alternatively, for H1 and H2, an underline-style is available:

Heading 1
=========

Heading 2
---------

## Text Formatting

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

~~This text is strikethrough~~

## Blockquotes

> This is a blockquote.
>
> This is part of the same blockquote.

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Lists

### Unordered List

*   Item 1
*   Item 2
    *   Item 2a
    *   Item 2b

### Ordered List

1.  Item 1
2.  Item 2
3.  Item 3
    1.  Item 3a
    2.  Item 3b

## Code

This is `inline code`.

```javascript
// This is a javascript code block
function greet(name) {
  console.log("Hello, " + name + "!");
}
greet("World");
```

```python
# This is a python code block
def hello(name):
    print(f"Hello, {name}!")

hello("World")
```

## Horizontal Rule

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

## Links

[GitHub](http://github.com)

[GitHub with title](http://github.com "GitHub Homepage")

## Images

![Alt text for image](https://via.placeholder.com/150 "Optional title")

## Tables

| Header 1 | Header 2 | Header 3 |
| :--- | :------: | ---: |
| Align Left | Align Center | Align Right |
| Cell 1 | Cell 2 | Cell 3 |
| Cell 4 | Cell 5 | Cell 6 |

## Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## Highlighting

Use two equal signs to ==highlight text==.
