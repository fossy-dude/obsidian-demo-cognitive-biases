# 1. Introduction to Markdown

## 1.1. Headings

You can create different levels of headings using hash symbols (`#`).

### 1.1.1. Third Level Heading

## 1.2. Paragraphs and Line Breaks

This is a paragraph of text. Markdown automatically handles line wrapping.

To create a new paragraph, use a blank line between blocks of text.

This is a second paragraph.

To force a line break within a paragraph, end the line with two spaces.  
This line is a new line within the same paragraph.

## 1.3. Emphasis

You can emphasize text using asterisks or underscores.

*Italic text* or _italic text_
**Bold text** or __bold text__
***Bold and italic text*** or ___bold and italic text___
~~Strikethrough text~~

## 1.4. Lists

### 1.4.1. Unordered Lists

- Item one
- Item two
  - Nested item
- Item three

### 1.4.2. Ordered Lists

1. First item
2. Second item
   1. Nested ordered item
3. Third item

### 1.4.3. Task Lists

- [x] Completed task
- [ ] Incomplete task

## 1.5. Code

### 1.5.1. Inline Code

You can include `inline code` using backticks.

### 1.5.2. Code Blocks

```python
def hello_world():
    print("Hello, Markdown!")
```

# 2. Advanced Features

## 2.1. Callouts

> [!info] What if your callouts could stand out like this?

> [!warning] This format is extremely addictive

## 2.2. Links

Here is a [link](www.google.com) to google

## 2.3. Embedded Assets

This is a tabby cat:

![This is a tabby cat](https://upload.wikimedia.org/wikipedia/commons/4/4d/Cat_November_2010-1a.jpg)

You can embed many other formats. Obsidian supports PDFs & Audio files as well (As long as they are sourced from some relative path)