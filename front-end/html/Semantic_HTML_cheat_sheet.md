- [Semantic HTML cheat sheet](#semantic-html-cheat-sheet)
  * [Sectioning tags](#sectioning-tags)
    + [`<header>`](#header)
    + [`<nav>`](#nav)
    + [`<footer>`](#footer)
    + [`<main>`](#main)
    + [`<aside>`](#aside)
    + [`<article>`](#article)
    + [`<section>`](#section)
    + [`<details>`](#details)
    + [`<summary>`](#summary)
    + [`<h1><h2><h3><h4><h5><h6>`](#h1h2h3h4h5h6)
  * [Content tags](#content-tags)
    + [`<blockquote>`](#blockquote)
    + [`<dd>`](#dd)
    + [`<dl>`](#dl)
    + [`<dt>`](#dt)
    + [`<figcaption>`](#figcaption)
    + [`<figure>`](#figure)
    + [`<hr>`](#hr)
    + [`<li>`](#li)
    + [`<menu>`](#menu)
    + [`<ol>`](#ol)
    + [`<p>`](#p)
    + [`<pre>`](#pre)
    + [`<ul>`](#ul)
  * [Inline tags](#inline-tags)
    + [`<a>`](#a)
    + [`<abbr>`](#abbr)
    + [`<b>`](#b)
    + [`<br>`](#br)
    + [`<cite>`](#cite)
    + [`<code>`](#code)
    + [`<data>`](#data)
    + [`<em>`](#em)
    + [`<i>`](#i)
    + [`<mark>`](#mark)
    + [`<q>`](#q)
    + [`<s>`](#s)
    + [`<samp>`](#samp)
    + [`<small>`](#small)
    + [`<span>`](#span)
    + [`<strong>`](#strong)
    + [`<sub>`](#sub)
    + [`<sup>`](#sup)
    + [`<time>`](#time)
    + [`<u>`](#u)
    + [`<var>`](#var)
  * [Embedded content and media tags](#embedded-content-and-media-tags)
    + [`<audio>`](#audio)
    + [`<canvas>`](#canvas)
    + [`<embed>`](#embed)
    + [`<iframe>`](#iframe)
    + [`<img>`](#img)
    + [`<object>`](#object)
    + [`<picture>`](#picture)
    + [`<video>`](#video)
    + [`<source>`](#source)
    + [`<svg>`](#svg)
  * [Table tags](#table-tags)
    + [`<table>`](#table)
    + [`<thead>`](#thead)
    + [`<tbody>`](#tbody)
    + [`<tfoot>`](#tfoot)
    + [`<tr>`](#tr)
    + [`<td>`](#td)
    + [`<th>`](#th)
    + [`<caption>`](#caption)
    + [`<colgroup>`](#colgroup)
    + [`<col>`](#col)


# Semantic HTML cheat sheet

There are hundreds of semantic tags available to help describe the meaning of your HTML documents. Below is a cheat
sheet with some of the most common ones you’ll use in this course and in your development career.

## Sectioning tags

Use the following tags to organize your HTML document into structured sections.

### `<header>`

The `<header>` tag is used to wrap introductory content for a page or section. This could be a logo, navigation, search
form, or anything else that is relevant to the content of the section.
The web page header often contains the website branding or logo.

### `<nav>`

The `<nav>` tag is used to wrap a set of navigation links. This could be a list of links to other pages on the site, or
links to other sites. The navigation links of a section or the web page.

### `<footer>`

The `<footer>` of a content section or the web page. On a web page, it often contains *secondary links*, the *copyright
notice*, *privacy policy* and *cookie policy* links.

### `<main>`

Specifies the main content of a section or the web page. The main content area consists of content that is directly
related to or expands upon the central topic of a document, or the central functionality of an application.

### `<aside>`

A secondary set of content that is not required to understand the main content. The `<aside>` tag can be used for
sidebar content, such as a list of related links, or a biography.

### `<article>`

An independent, self-contained block of content such as a blog post or product.

### `<section>`

A standalone section of the document that is often used within the body and article elements.

### `<details>`

A collapsed section of content that can be expanded if the user wishes to view it.

### `<summary>`

Specifies the summary or caption of a `<details>` element.

### `<h1><h2><h3><h4><h5><h6>`

Headings on the web page. `<h1>` indicates the most important heading whereas `<h6>` indicates the least important.

## Content tags

### `<blockquote>`

Used to describe a quotation.

### `<dd>`

Used to define a description for the preceding `<dt>` element.

### `<dl>`

Used to define a description list. The `<dl>` tag is used to define a description list.

### `<dt>`

Used to describe terms inside `<dl>` elements. The `<dt>` tag is used to define a term/name in a description list.

### `<figcaption>`

Defines a caption for a photo image.

### `<figure>`

Applies markup to a photo image. The `<figure>` tag is used to group media content, and its caption, in a document.

### `<hr>`

Adds a horizontal line to the parent element. The `<hr>` tag is an empty element and does not have a closing tag.

### `<li>`

Used to define an item within a list.

### `<menu>`

A semantic alternative to `<ul>` tag. The `<menu>` tag is used to group a set of related items in no particular order.

### `<ol>`

Defines an ordered list. Each item in the list is marked with a number. The `<ol>` tag is used to group a set of
related items in a specific order.

### `<p>`

Defines a paragraph. The `<p>` tag is used to group a set of related sentences in a paragraph.

### `<pre>`

Used to represent preformatted text. Typically rendered in the web browser using a monospace font.

### `<ul>`

Unordered list of items. Each item is marked with a bullet point. The `<ul>` tag is used to group a set of
related items in no particular order.

## Inline tags

### `<a>`

An anchor link to another HTML document. The `href` attribute specifies the URL of the page the link goes to.

### `<abbr>`

Specifies that the containing text is an abbreviation or acronym. The text is usually displayed in italics.

### `<b>`

Bolds the containing text. When used to indicate importance use `<strong>` instead.

### `<br>`

A line break. Moves the subsequent text to a new line. The `<br>` tag is an empty element and does not have a closing

### `<cite>`

Defines the title of creative work (for example a book, poem, song, movie, painting or sculpture). The text in
the `<cite>` element is usually rendered in italics.

### `<code>`

Indicates that the containing text is a block of computer code. The text is usually displayed in a monospace font.

### `<data>`

Indicates machine-readable data. The value of the data attribute should be a valid URL.

### `<em>`

Emphasizes the containing text. Used to indicate stress or emphasis.

### `<i>`

The containing text is displayed in italics. Used to indicate idiomatic text or technical terms.

### `<mark>`

The containing text should be marked or highlighted. Used to indicate search results.

### `<q>`

The containing text is a short quotation. The quotation is wrapped in double quotation marks.

### `<s>`

Displays the containing text with a strikethrough or line through it.

### `<samp>`

The containing text represents a sample. The text is usually displayed in a monospace font.

### `<small>`

Used to represent small text, such as copyright and legal text. The text is usually displayed in a smaller font.

### `<span>`

A generic element for grouping content for CSS styling. The `<span>` element does not have any semantic meaning.

### `<strong>`

Displays the containing text in bold. Used to indicate importance. When used to indicate stress or emphasis use `<em>`
instead.

### `<sub>`

The containing text is subscript text, displayed with a lowered baseline. Used to indicate chemical formulas.

### `<sup>`

The containing text is superscript text, displayed with a raised baseline.

### `<time>`

A semantic tag used to display both dates and times. The value of the time attribute should be a valid URL.

### `<u>`

Displays the containing text with a solid underline. The text is usually displayed in a monospace font.

### `<var>`

The containing text is a variable in a mathematical expression. The text is usually displayed in a monospace font.

## Embedded content and media tags

### `<audio>`

Used to embed audio in web pages.

### `<canvas>`

Used to render 2D and 3D graphics on web pages.

### `<embed>`

Used as a containing element for external content provided by an external application such as a media player or plug-in
application.

### `<iframe>`

Used to embed a nested web page.

### `<img>`

Embeds an image on a web page.

### `<object>`

Similar to <embed> but the content is provided by a web browser plug-in.

### `<picture>`

An element that contains one `<img>` element and one or more `<source>` elements to offer alternative images for
different displays/devices.

### `<video>`

Embeds a video on a web page.

### `<source>`

Specifies media resources for `<picture>`, `<audio>` and `<video>` elements.

### `<svg>`

Used to define Scalable Vector Graphics within a web page.

## Table tags

### `<table>`

Defines a table element to display table data within a web page.

### `<thead>`

Represents the header content of a table. Typically, contains one `<tr>` element.

### `<tbody>`

Represents the main content of a table. Contains one or more `<tr>` elements.

### `<tfoot>`

Represents the footer content of a table. Typically, contains one `<tr>` element.

### `<tr>`

Represents a row in a table. Contains one or more <td> elements when used within `<tbody>` or `<tfoot>`. When used
within `<thead>`, contains one or more `<th>` elements.

### `<td>`

Represents a cell in a table. Contains the text content of the cell.

### `<th>`

Defines a header cell of a table. Contains the text content of the header.

### `<caption>`

Defines the caption of a table element.

### `<colgroup>`

Defines a semantic group of one or more columns in a table for formatting.

### `<col>`

Defines a semantic column in a table.

