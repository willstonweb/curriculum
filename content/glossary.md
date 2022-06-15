---
title: Bootcamp Glossary
description: Willston Web Coding Bootcamp glossary
---

## Terms

### `SEO`

- Search Engine Optimization
- Good `SEO` helps your ranking on search engines like Google and DuckDuckGo
- Q: Why does Apple, the company come up before actual apples when you search
  for `apple` in a search engine?
- A: They have good SEO and many people visit their website

### `index.html`

- The starting HTML _home_ page for a website

### `Tag`

- Every tag starts and ends with angle brackets (`<` and `>`). Usually, two tags
  make up an `HTML` element

#### `Opening tag`

- The element's name, attribues, and values. Opening tags do not have a `/`
  after the first `<`. Example:
    ```html
    <a href="https://www.comunidadva.org" target="_blank">
    ```
#### `Closing tag`

- `/` after the first `<` and the element's name. Example:
    ```html
    </a>
    ```
#### `Self-closing tag`

- An element that only has one tag, like the image tag. It can have a `/` before
  the last `>`, but it is not necessary. Example:
    ```html
    <img src="http://www.superchickenfallschurch.com/wp-content/uploads/2014/12/logo.png" alt="Super Chicken Falls Church logo">
    ```

### `Element`

- An HTML item that has a specific that usually has opening and
  closing tags. Elements can be nested inside of other elements. Example:
    ```html
    <h1>My Website</h1>
    ```
    ```html
    <body>
        <h1>My Website</h1>
    </body>
    ```

### `Attribute`

- A piece of information about the element. It goes in the opening tag and are
  separated with spaces. An `=` should immediately follow and the `value` should
  be surrounded by `"` on each side. Example:
    ```html
    <a href="https://www.google.com" target="_blank">
    ```
- The attributes are `href` and `target`
- The values are `https://www.google.com` and `_blank`

### `Comment`

- You use for reading and documenting your code. You can also
  comment out multiple lines if you want to test if they are causing issues.
  Examples:
    ```html
    <!-- TODO: This is a Comment to help me read my code -->
    ```
- You can surround anything inside the following two tags to make them
  effectively have no effect on the HTML website: `<!--` (opening tag) `-->`
  (closing tag)
    ```html
    <!--
    <h3>Bad HTML</h3>
    <p>This HTML is messing up the website</p>
    <p>Because it is commented out, it has no effect on the website anymore</p>
    -->
    ```

### `URL`

- A website's address. Examples:
    - `https://www.google.com`
    - `http://superchickenfallschurch.com`

### `File path`

- The location of a file such as `index.html` or `logo.png`
    ```
    ~/Code/hello-world/logo.png
    ```
    ```
    ~/Code/hello-world/index.html
    ```

### `HTTPS`

- Hypertext Transfer Protocol _Secure_
    - The `s` (secure) part is optional, but should be used whenever possible

## Elements

- `<!DOCTYPE html>` = the first line of every HTML file. It makes sure the
  browser knows we are writing HTML
- `<html></html>` = first element after `<!DOCTYPE html>`
- `<h1></h1>` = header 1
- `<h2></h2>` = header 2
- `<h3></h3>` = header 3
- `<h4></h4>`= header 4
- `<h5></h5>` = header 5
- `<h6></h6>` = header 6
- `<p></p>` = paragraph
- `<img>` = image. This is a self-closing tag.
- `<a></a>` = anchor (link)
- `<body></body>` = the body of the website. Everything that shows up on the
  page goes between these two tags
    ```html
    <body>
        <p>Hello world.</p>
    </body>
    ```
- `<main></main>` = main section of elements to help [SEO](#seo)
    ```html
    <body>
        <h1>My Website</h1>
        <main>
          <h2>Second heading</h2>
          <p>Here is some text</p>
        </main>
    </body>
    ```
- `<section></section>` = section element can be used to help group parts of the
  page together
    ```html
    <section>
        <img src="http://www.superchickenfallschurch.com/wp-content/uploads/2014/12/logo.png" alt="Super Chicken Falls Church logo">
        <p>Super Chicken</p>
    </section>
    ```

## Attributes

- Make sure to put a space before the attribute and after the element name, add
  an `=` after the attribute, and put the `value` inside of `""`. Example:
    ```html
    <a href="https://www.google.com" target="_blank">
    ```
    - `href` is an attribute with the value `https://www.google.com`
    - `target` is an attribute with the value `_blank`

### `src`

- External resource or source
- It is used to pull an image's [web address](#url) or [file
  path](#file-path)

### `href`

- Hypertext reference
- It is used to determine which [URL](#url) a user is taken to when clicking
  a link

### `target`

- It is used to open a [URL](#url) in a new tab when the value is `_blank`
    ```html
    target="_blank"
    ```
