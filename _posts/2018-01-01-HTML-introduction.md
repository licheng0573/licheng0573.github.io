---
layout: articles
title: "HTML introduction"
categories: HTML, CSS, JavaScript
permalink: HTML-introduction.html
tags: [HTML]
sidebar: 
  nav: docs-en
---

## What is HTML?

HTML is the standard markup language for creating Web pages.

- HTML stands for Hyper Text Markup Language
- HTML describes the structure of Web pages using markup
- HTML elements are the building blocks of HTML pages
- HTML elements are represented by tags
- HTML tags label pieces of content such as &quot;heading&quot;, &quot;paragraph&quot;, &quot;table&quot;, and so on
- Browsers do not display the HTML tags, but use them to render the content of the page

## A Simple HTML Document

### Example

    <!DOCTYPE html>
    <html>
    <head>
    <title>Page Title</title>
    </head>
    <body>
    
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
    
    </body>
    </html>

### Example Explained

- The `<!DOCTYPE html>` declaration defines this document to be HTML5
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the document
- The `<title>` element specifies a title for the document
- The ``<body>` element contains the visible page content
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

## HTML Tags

HTML tags are element names surrounded by angle brackets:

    <tagname>content goes here...</tagname>

- HTML tags normally come  **in pairs**  like `<p>` and `</p>`
- The first tag in a pair is the  **start tag,**  the second tag is the  **end tag**
- The end tag is written like the start tag, but with a  **forward slash**  inserted before the tag name

**Tip:**  The start tag is also called the  **opening tag** , and the end tag the  **closing tag**.

## Web Browsers

The purpose of a web browser (Chrome, IE, Firefox, Safari) is to read HTML documents and display them.

The browser does not display the HTML tags, but uses them to determine how to display the document.
![此处输入图片的描述][1]


[1]: https://www.w3schools.com/html/img_chrome.png

## The <!DOCTYPE> Declaration
The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.
It must only appear once, at the top of the page (before any HTML tags).
The `<!DOCTYPE>` declaration is not case sensitive.
The `<!DOCTYPE>` declaration for HTML5 is:

    <!DOCTYPE html>


## HTML Versions

Since the early days of the web, there have been many versions of HTML:

| **Version** | **Year** |
| --- | --- |
| HTML | 1991 |
| HTML 2.0 | 1995 |
| HTML 3.2 | 1997 |
| HTML 4.01 | 1999 |
| XHTML | 2000 |
| HTML5 | 2014 |