---
title: "Markdown Tutorial"
date: 2022-03-01T12:14:34+06:00
image: "images/portfolio/markdown.png"
tags: ["design"]
description: "Markdown Language"
draft: false
---

- [*What is Markdown?*](#what-is-markdown)
- [*What is Markdown File Extension?*](#what-is-markdown-file-extension)
- [*Advantages*](#advantages)
- [*Why Use Markdown?*](#why-use-markdown)
- [*How do you open markdown files?*](#how-do-you-open-markdown-files)
- [*Basic Syntax*](#basic-syntax)
  - [1. Headings](#1-headings)
      - [Simple Text Styles](#simple-text-styles)
  - [2. Paragraphs](#2-paragraphs)
  - [3. Blockquotes](#3-blockquotes)
      - [Multiple Quote](#multiple-quote)
      - [Nested Quote](#nested-quote)
  - [4. Lists](#4-lists)
      - [Nested Lists](#nested-lists)
  - [5. Horizontal Rule](#5-horizontal-rule)
  - [6. Links](#6-links)
      - [Reference Links](#reference-links)
  - [7. Images](#7-images)
      - [Reference Image](#reference-image)
      - [Relative Links Image](#relative-links-image)
- [*Extended Syntax*](#extended-syntax)
  - [1. Fenced Code Block](#1-fenced-code-block)
  - [2. Task Lists](#2-task-lists)
  - [3. Tables](#3-tables)
      - [Table Alignment](#table-alignment)
  - [4. Emoji](#4-emoji)
      - [Using Emoji Shortcodes](#using-emoji-shortcodes)
  - [5. Toggle](#5-toggle)
  - [6. Subscript & Superscript](#6-subscript--superscript)
- [*Markdown Cheatsheet - Basic Syntax*](#markdown-cheatsheet---basic-syntax)
- [*Markdown Cheatsheet - Extended Syntax*](#markdown-cheatsheet---extended-syntax)

Markdown is a lightweight markup language designed to be human-friendly and easily convertible to HTML.

# *What is Markdown?*

* Markdown is a lightweight markup language, originally created by John Gruber and Aaron Swartz allowing people “to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally
valid XHTML (or HTML). *Source: http://en.wikipedia.org/wiki/Markdown*
* It helps users to write plain text and convert it to multiple formats
like HTML, pdf, etc.
* It contains two things
    1. Writing text content with special syntax
    2. Parser to convert this content into different output

# *What is Markdown File Extension?*

- There is no office extension defined for these types of files
- We can create a plain text file with the .md extension to write content for websites
- We can create a files with different extensions for markdown files
  - .markdown
  - .md
  - .mkd
  - .mkdown
  - .text
  - .mdown
- Some of the popular vendors use HTML extensions
- Github uses markdown and mdown extensions
- GitHub uses the standard file extension as .md

# *Advantages*

1. It is easy to read and write the plain text that converts to a Rich HTML document
2. Easy to learn and write content effectively for technical and non-technical people
3. Easy to test the content locally and easy to add/update and delete content
4. Support for popular visual editors
5. Extending syntax to provide custom elements like audio, video, etc
6. Easily share this content between different devices
7. Markdown is standard for writing content in GitHub, GitLab, and Reddit

# *Why Use Markdown?*

* **Markdown can be used for everything.** People use it to
create websites, documents, notes, books, presentations, email messages,
and technical documentation
* **Markdown is portable.** Files containing Markdown-formatted text can be
opened using virtually any application
* **Markdown is platform independent.** You can create Markdown-formatted text on any device running any operating system
* **Markdown is future proof.** Even if the application you’re using stops working at some point in the future, you’ll still be able to read your Markdown-formatted text using a text editing application
* **Markdown is everywhere.** Websites like Reddit and GitHub support Markdown,
and lots of desktop and web-based applications support it

# *How do you open markdown files?*

- These files open in a simple text editor or Integrated Development editors like Visual Studio, Atom Sublime Text, Notepad++, and Intelli IDEA in Windows, UNIX, and MAC OS.
- There are several online Markdown editors that you can use to try writing in Markdown. Dillinger is one of the best online Markdown editors. Just open the site and start typing in the left pane. A preview of the
rendered document appears in the right pane.

# *Basic Syntax*

## 1. Headings

You can create HTML elements through easily by prepending the text you want to be in that element by a number of hashes (#).

![Heading](/images/markdown/heading.JPG)

Markdown also provides us with two alternative ways of indicating h1 and h2

![Heading1](/images/markdown/heading1.JPG)


#### Simple Text Styles

* Text can be easily styled as italic or bold using markdown

<img src="/images/markdown/textstyle.JPG" width="100%" height="auto" />

## 2. Paragraphs

- Paragraphs are a one or multiple adjacent lines of text separated by
one or multiple blank lines.

![Paragraph](/images/markdown/paragraph.JPG)

## 3. Blockquotes

* To create a blockquote, add a > in front of a paragraph.

![blockquote](/images/markdown/quote1.JPG)

![blockquote](/images/markdown/quote.JPG)

#### Multiple Quote

![Multiple Quote](/images/markdown/mquote1.JPG)

![Multiple Quote](/images/markdown/mquote.JPG)

#### Nested Quote

![Nested Quote](/images/markdown/nquote1.JPG)

![Nested Quote](/images/markdown/nquote.JPG)

## 4. Lists

- You can make an unordered list by preceding one or more lines of text with - or *
- To order your list, precede each line with a number

![List](/images/markdown/list1.JPG)

![List](/images/markdown/List.JPG)

#### Nested Lists

* You can create a nested list by indenting one or more list items below another item.
* To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom, you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

![Nested List](/images/markdown/nlist1.JPG)

![Nested List](/images/markdown/nlist.JPG)

## 5. Horizontal Rule

Horizontal rules (<hr/>) are easily added with three or more asterisks or hyphens, with or without spaces.

![Horizontal Rule](/images/markdown/hrule.JPG)

***

## 6. Links

1. One of the best things about markdown is how easy it is to make links. Put the text to display in hard brackets [] followed by the url in parentheses ().
2. You can also add a link title using quotes inside the parentheses.
3. Relative paths work too.

![Links](/images/markdown/link1.JPG)

![Links](/images/markdown/link.JPG)

 
#### Reference Links

- Markdown also supports reference style links
- The title can also be in single quotes or in parentheses, or omitted entirely. The references can be anywhere in your document and the reference IDs can be anything so long as they are unique.

![Reference Link](/images/markdown/rlink1.JPG)

![Reference Link](/images/markdown/rlink.JPG)

## 7. Images

- You can display an image by adding ! and wrapping the alt text in [ ]. Then wrap the link for the image in parentheses ()
- And reference style works as expected

![Image](/images/markdown/image.JPG)

<img src="/images/markdown/mercedes.jpg" width="100%" height="auto"/>

#### Reference Image

![Reference Image](/images/markdown/rimage.JPG)

<img src="/images/markdown/mercedes1.jpg" width="100%" height="auto"/>

#### Relative Links Image

- Here are some examples for using relative links to display an image.

<img src="/images/markdown/rlinkimage.JPG" width="100%" height="auto"/>

# *Extended Syntax*

## 1. Fenced Code Block

* You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown
* To format code or text into its own distinct block, use triple
backticks

![Fenced Code Block](/images/markdown/qcode1.JPG)

![Fenced Code Block](/images/markdown/qcode.JPG)

## 2. Task Lists

- To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].

![Task Lists](/images/markdown/tlist1.JPG)

![Task Lists](/images/markdown/tlist.JPG)

## 3. Tables

* To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. For compatibility, you should also add a pipe on either end of the row.

![Table](/images/markdown/table1.JPG)

![Table](/images/markdown/table.JPG)

#### Table Alignment

* You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row

![Table Alignment](/images/markdown/tablea1.JPG)

![Table Alignment](/images/markdown/tablea.JPG)

## 4. Emoji

* There are two ways to add emoji to Markdown files: copy and paste the emoji into your Markdown-formatted text, or type emoji shortcodes

#### Using Emoji Shortcodes

* Some Markdown applications allow you to insert emoji by typing emoji shortcodes. These begin and end with a colon and include the name of an emoji

![Emoji](/images/markdown/emoji1.JPG)

![Emoji](/images/markdown/emoji.JPG)

## 5. Toggle

![Toggle](/images/markdown/toggle.JPG)

<details>
<summary>This is a Toggle</summary>
Contents of toggle.
</details>

## 6. Subscript & Superscript

***Subscript*** - This isn’t common, but some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. To create a subscript, use one tilde symbol (~) before and after the characters.

***Superscript*** - This isn’t common, but some Markdown processors allow you to use superscript to position one or more characters slightly above the normal line of type. To create a superscript, use one caret symbol (^) before and after the characters.

![Subscript&Superscript](/images/markdown/script1.JPG)

![Subscript&Superscript](/images/markdown/script.JPG)

# *Markdown Cheatsheet - Basic Syntax*

<img src="/images/markdown/basic.JPG" width="100%" height="auto"/>

# *Markdown Cheatsheet - Extended Syntax*

<img src="/images/markdown/extended.JPG" width="100%" height="auto"/>
