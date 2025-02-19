# Technical-Notes

# Basic Syntax Test

### Headers (ATX style)
# First Level Header
## Second Level Header
### Third Level Header

### Headers (Setext style)
First Level Header
==================

Second Level Header
------------------

### Line Breaks (hard and soft)
Here's a line  
with a hard break (two spaces)

Here's a line
with a soft break

### Nested Lists
1. First item
   * Nested unordered
   * Another bullet
2. Second item
   1. Nested ordered
   2. Another number
3. Third item

### Emphasis
*Italic text*
**Bold text**
***Bold and italic***
_Underscore italic_
__Underscore bold__
___Triple underscore___

### Links
[Basic link](https://example.com)
[Link with title](https://example.com "Link title")
<https://example.com>
<email@example.com>

### Images
![Alt text](image.jpg)
![Alt text with title](image.jpg "Image title")

### Blockquotes
> Simple blockquote
>> Nested blockquote
> * List in blockquote
> # Header in blockquote

### Code
`Inline code`

```python
def hello_world():
    print("Hello, World!")
```

    Indented code block
    (4 spaces or 1 tab)

### Horizontal Rules
---
***
___

## Extended Syntax

### Tables
| Header 1 | Header 2 | Aligned Right |
|----------|:---------|-------------:|
| Cell 1   | Cell 2   | Cell 3       |
| Cell 4   | Cell 5   | Cell 6       |

### Task Lists
- [x] Completed task
- [ ] Incomplete task
  - [x] Nested completed task
  - [ ] Nested incomplete task

### Footnotes
Here's a text with a footnote[^1]
And another one[^2]

[^1]: First footnote
[^2]: Second footnote

### Definition Lists
Term 1
: Definition 1
: Another definition

Term 2
: Definition 2

### Strikethrough
~~Struck through text~~

### Superscript/Subscript
H~2~O
X^2^

### Automatic Links
https://example.com
email@example.com

## GitHub/GitLab Specific Features

### Mention
@username

### Issue/PR References
#123
username/repository#123

### Syntax Highlighting with Code
```javascript
function example() {
    return "Hello, World!";
}
```

### Task Lists (GitHub Style)
- [x] This is done
- [ ] This isn't done

## MultiMarkdown Specific Features

### Citations
This is a statement[p. 23][#citation]

[#citation]: Author, Title (Year)

### Glossary
[?term]: Definition of the term
Term[?term]

### Math
$E = mc^2$

### Cross References
[Chapter 1]

### Metadata
Title: Document Title
Author: Author Name
Date: 2025-02-18

### HTML Support
<div class="custom-class">
  <p>Custom HTML content</p>
</div>
