# Thing 

### Lesson 1: HTML Basics and Tags ###
Objective: Introduce students to the structure of a web page and the foundational HTML tags.

#### What is HTML?

HTML stands for HyperText Markup Language.

It's the language used to create web pages.

Web pages are built using a series of HTML tags that tell the browser how to display content.

## Basic Structure of an HTML Document

`<!DOCTYPE html>`: Declares the document type.

`<html>`: The root element of an HTML page.

`<head>`: Contains meta-information about the HTML document (like title and links to CSS).

`<title>`: The title of the webpage (appears in the browser tab).

`<body>`: Contains the content of the webpage.

### Essential Tags 

`<h1> to <h6>`: Headings, with `<h1>` being the largest and `<h6`> the smallest.

`<p>`: Paragraphs.

`<ul>, <ol>, <li>`: Unordered and ordered lists with list items.

`<a href="">`: Links to other web pages.

`<img src="" alt="">`: Images


 ## Lesson 2: CSS Styling


### What is CSS?

CSS stands for Cascading Style Sheets.
It controls the look and feel of a web page.
HTML is about structure; CSS is about style.
### CSS Syntax

A CSS rule consists of a selector and a declaration block.

Example:``` h1 { color: blue; font-size: 24px; }```

The selector `(h1)` targets which elements you want to change.

The declaration block `(color: blue; font-size: 24px;) `specifies the style.

### Common CSS Properties

`color:` Text color.

`font-size:` Size of the text.

`background-color:` Background color of an element.

`margin:` and `padding:` Space around elements.

`border:`  Adds a border around an element.

## Linking CSS to HTML

Inline CSS: Styles directly within an HTML tag (e.g., <p style="color: red;">).
Internal CSS: Styles within the <style> tag in the HTML <head>.
External CSS: A separate CSS file linked with <link>.
Activity: Style the Previous Web Page


## Lesson 3: Embedding Videos, Adding Images, and Links
Objective: Teach students how to enhance their web pages by embedding multimedia and creating links.

Embedding Images

Using the <img> tag to display images on a web page.
Attributes: src (source), alt (alternative text), width, and height.
Example: <img src="path/to/image.jpg" alt="Description of image">
Adding Links

The <a> tag for creating hyperlinks.
Attributes: href (hyperlink reference) and target (where to open the link).
Example: <a href="https://www.example.com" target="_blank">Visit Example</a>
Embedding Videos

Using the <video> tag to embed video files.
Attributes: src, controls (to show video controls), autoplay, and loop.
Example: <video src="video.mp4" controls>
YouTube and Other External Videos

Using <iframe> to embed videos from platforms like YouTube.
Example: <iframe width="560" height="315" src="https://www.youtube.com/embed/videoID" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
