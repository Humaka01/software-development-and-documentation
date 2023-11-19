# Markdown Quick Guide

## 1. Headings

To create headings in Markdown, use the `#` symbol followed by a space. Heading levels are indicated by the number of `#` symbols. For example:

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5 - Which is same as **Bold**
```

## 2. Emphasis
Emphasize text using bold or italic styles:
- **Bold Text**: Surround the desired text with double asterisks `**` on each side.
```markdown
**Bold Text**
```
- **Italic Text**: Place underscores `_` around the text you want to emphasize.
```markdown
_Italic Text_
```
## 3. Lists
Markdown supports both ordered and unordered lists:
- **Ordered List**: Use numbers followed by a period, and Markdown will recognize it as an ordered list, for example:
```markdown
1. Item one.
2. Item two.
```
will be rendered as follows:
1. Item one.
2. Item two.
- **Unordered List**: Utilize the minus sign `-` to create unordered list items, for example:
```markdown
- Item A
- Item B
```

will be rendered as:
- Item A
- Item B

## 4. Links
Insert links using the following syntax:
- **Inline Links**: Place clickable text in square brackets, followed by the link in parentheses, for instance:
```markdown
[Google](https://www.google.com/)
```
will be rendered:
[Google](https://www.google.com/)

## 5. Images
Include images in your Markdown document with the following formats:
- **Absolute Link Example:**
```markdown
![ASU Logo](https://admission.asu.edu.jo/assets/media/image/ASU-Logo.png)
```
will be rendered as:

![ASU Logo](https://admission.asu.edu.jo/assets/media/image/ASU-Logo.png)

- **Relative Link Example:**
```markdown
![ASU Logo](images/ASU-Logo.png)
```
will be rendered as:

![ASU Logo](images/ASU-Logo.png)

_* Remember to ensure correct folder structures and relative paths when using images._
## 6. Adding a New Line
To insert a new line, you can use the `<br>` tag.

For example, the following Markdown code:
```markdown
This is the first line.<br>This is the second line.
```
will be rendered as:
```markdown
This is the first line.
This is the second line.
```

## 7. Code Blocks with Triple Backticks

To show code or text in a neat block, just use triple backticks (```). You can do it in two ways: with or without specifying the language.

- **Without Language Specification:**
For example, the following code:

```
\```
This is a code block without language specification.
\```
```
will be rendered as:
```
This is a code block without language specification.
```

- **With Language Specification:**
You can specify the language by adding it after the initial triple backticks (```), for instance:

```
\```python
def greet(name):
    print(f"Hello, {name}!")

greet("World")
\```
```
will be rendered in markdown as:
```python
def greet(name):
    print(f"Hello, {name}!")

greet("World")
```

- **Inline Code with Single Backticks:**
To highlight a single character or a small code snippet within a sentence, enclose the desired text with single backticks on both sides, for instance:
```
Code example: `myFunction()`
To format text as code: `word`.
To format a single character as code: `p`
```
When rendered in Markdown, it will appear as:
Code example: `myFunction()`
To format text as code: `word`.
To format a single character as code: `p`

_* Using single backticks allows you to incorporate code elements seamlessly into your sentences._