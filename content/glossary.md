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

#### `Opening Bracket`

- This symbol is used at the _beginning_ of very [tag](#tag)
- It is also known as the 'less than sign' in math and is sometimes referred to
  as a 'left angle bracket'
```html
<
```

#### `Closing Bracket`

- This sybmol is used at the _end_ of every [tag](#tag)
- It is known as the 'greater than sign' in math and is sometimes referred to as
  a 'right angle bracket'
```html
>
```

### `Element`

> To see all valid `HTML` elements, visit
> https://developer.mozilla.org/en-US/docs/Web/HTML/Element or search for
> `mozilla elements` in a search engine

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

#### `Parent Element`

- Any element that has other elements inside its [opening](#opening-tag) and
  [closing tags](#closing-tag) is a **parent element**
  - In this example, `<main></main>` is the **parent element**
    ```html
    <main>
      <h1>My Website</h1>
      <h2>By Ricardo</h2>
      <p>Welcome to my website; I am happy you are here.</p>
      <img src="https://www.example.com/images/logo.png" alt="Ricardo Logo">
    </main>
    ```

#### `Child Element`

- Any element inside the opening and closing tags of another element is a
  **child element**
    - In example below, each of the following are child elements:
      - `<h1></h1>`
      - `<h2></h2>`
      - `<p></p>`
      - `<img>`
    ```html
    <main>
      <h1>My Website</h1>
      <h2>By Ricardo</h2>
      <p>Welcome to my website, I am happy you are here</p>
      <img src="https://www.ricardowebsite.com" alt="Ricardo Logo">
    </main>
    ```

### `Attribute`

> To see all valid `HTML` attributes , visit
> https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes or search for
> `mozilla attributes` in a search engine

- A piece of information about the element. It goes in the opening tag and are
  separated with spaces. An `=` should immediately follow and the `value` should
  be surrounded by `"` on each side. In the following example, `href` and
  `target` are both attributes. The values are `https://www.google.com` and
  `_blank`
    ```html
    <a href="https://www.google.com" target="_blank">
    ```

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
- `<figure>` = used to group elements such as photos and special documents
  - `<figcaption>` = is normally a [child element](#child-element) of `<figure>`
  ```html
    <figure>
      <img src="https://order.subway.com/en-us/-/media/Project/Remote-Order/Images/Logo/subway-logo.png" alt="Subway logo">
      <figcaption>Subway logo</figcaption>
    </figure>
  ```
- `<strong></strong>` = all the text between this element will be **BOLDED**.
  ```
  <strong>This text will display bold</strong>
  ```

   <strong>This text will display bold</strong>

- `<em></em>` = all the text between this element will be _emphasized_.
  ```html
  <em>This text will display emphasized</em>
  ```

  <em>This text will display emphasized</em>

- `<li></li>` = list item element. Typically the [child](#child-element) of an
  ordered or unordered list.
  - The item will appear as a bullet by default unless in an ordered list
  ```html
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  ```
- `<ul></ul>` = unordered list element. Is the [parent](#parent-element) of a group of list items
  - The list items will have bullets in front of them.
  ```html
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
  ```
- `<ol></ol>` = ordered list element. Is the [parent](#parent-element) of a group of list items.
  - The list items will have numbers in front of them.
  ```
    <ol>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ol>
    ```
- `<form></form>` = [parent](#parent-element) element for all elements that are
  apart of a web form.
- `<input>` = [self-closing](#self-closing-tag) tag that is used for different
  types of user input on a web form. It is typically a [child](#child-element)
  element of `<form>`.
- `<button></button>` = A button element used on a website for clicks and
  actions

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

### `width` & `height`

- Used to determine how much width or height content can take up of a
  [parent](#parent-element) element or the screen.
  - can be written in `px` (pixels) or `%` of the space.
  ```html
  <img width="50%" height="50%">
  <img width="400px" height="400px">
  ```

### `action`

- Where website input should be sent to after a form is submitted
  ```html
  <form action="https://willston.org/submit">
  ```

### `type`

- For an `<input>` element, what type of input should be entered (text,
  checkbox, radio button)?
  ```html
  <input type="radio">
  ```

### `value`

- Specifies the value of an `<input>` element
  ```html
  <input type="radio" value="yes">
  ```

## Prizes

### $200

Any student who completes the [first module](#module) of [freeCodeCamp's (New) Responsive
Web Design Certificate] will receive $200 and be able to keep their laptop.

[freeCodeCamp's (New) Responsive Web Design Certificate]: https://www.freecodecamp.org/learn/2022/responsive-web-design/

### New MacBook Air

The three students who complete the most steps in freeCodeCamp's (New)
Responsive Web Design Certificate will trade in their assigned laptop for a
brand new MacBook Air.

The student who completes the most steps will receive an additional $200 to the
$200 prize for a total of $400.

The student who completes the second most steps will receive an additional $100
to the $200 prize for a total of $300.

The student who completes the third most steps will not receive additional money
to the $200 prize for a total of $200.

### Additional $100 and a Trip to Busch Gardens

If every student who completes the one week bootcamp completes the first module
of freeCodeCamp's (New) Responsive Web Design Certificate, everyone will receive
an additional $100 and have the option to take a trip to Busch Gardens.

### Clarifying Terms

#### Certificate

The certificate is the 300 hour curriculum, such as the (New) Responsive Web
Design Certificate.

#### Course

A course is the next largest block of curriculum to a certificate, such as the
Learn HTML by Building a Cat Photo App course.

#### Lesson

A lesson is the next largest block of curriculum to a course, such as the first
step of the Learn HTML by Building a Cat Photo App.

#### Module

A module is a group of courses that ends in a certificate project. The first
module of freeCodeCamp's (New) Responsive Web Design Certificate includes the
following:

- The "Learn HTML by Building a Cat Photo App" course
- The "Learn Basic CSS by Building a Cafe Menu" course
- The "Learn CSS Colors by Building a Set of Colored Markers" course
- The "Learn HTML forms by Building a Registration Form" course
- The "Survey Form" certification project
