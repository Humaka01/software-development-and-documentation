
# Markdown Quick Guide

## 1. Headings

To create headings in Markdown, use the `#` symbol followed by a space. Heading levels are indicated by the number of `#` symbols. For example:

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5 - Which is same as **Bold**
###### Heading 6
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
![bengali-cat](https://basepaws.com/_next/image?url=https%3A%2F%2Fimages.ctfassets.net%2F7hqiona4456t%2F3Ks1FXaeWtNa8yHErHzQfA%2F592ee709464f16de0bae5d62f642142a%2Fbengal_cat__1_.jpg&w=640&q=75)
```
will be rendered as:

![bengali-cat](https://basepaws.com/_next/image?url=https%3A%2F%2Fimages.ctfassets.net%2F7hqiona4456t%2F3Ks1FXaeWtNa8yHErHzQfA%2F592ee709464f16de0bae5d62f642142a%2Fbengal_cat__1_.jpg&w=640&q=75)

>**`[bengali-cat]`** is the alternative text that will show up if the image is not available, so you can replace it with anything that gives meaning to your image.

- **Relative Link Example:**
```markdown
![ASU Logo](images/ASU-Logo.png)
```
will be rendered as:

![ASU Logo](images/ASU-Logo.png)

>Remember to ensure correct folder structures and relative paths when using images.

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

## 7. Code Blocks

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
When rendered in Markdown, it will appear as:<br>
Code example: `myFunction()`<br>
To format text as code: `word`.<br>
To format a single character as code: `p`

> Using single backticks allows you to incorporate code elements seamlessly into your sentences.

- **Blockquotes:**
To add a simple comment or block of nicely organized text we could use the `>` symbol, for example:
```
> This is a comment
```
will be rendered as:
> This is a comment

## 8. Tables
To create a simple table in markdown use the following format:

```
|Header 1|Header 2| Header 3|
|-----------|-----------|-----------|
|Content 1|Content 2|Content 3|
```
will be rendered as:
|Header 1|Header 2| Header 3|
|-----------|-----------|-----------|
|Content 1|Content 2|Content 3|

## 9. Tasks list
You can insert task list items using the following format:
```
- [x] Task 1
- [x] Task 2
- [ ] Task 3
```
>Don't forget to put in a space in between the brackets if you want the item not to be ticked, otherwise it will not render correctly.

will be rendered as follows:
- [x] Task 1
- [x] Task 2
- [ ]  Task 3
