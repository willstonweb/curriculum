---
title: CSS One Pager
description: Willston Web Coding CSS One Pager
---

## CSS

> To see all valid `CSS` properties , visit
> https://developer.mozilla.org/en-US/docs/Web/CSS/Reference or search for
> `mozilla css reference` in a search engine

- `CSS` = Cascading Style Sheets
    - This is the _"coding language"_ that helps stylize the look and feel of
      `html`
- `styles.css` = the main css file name that is typically used with `index.html`
    - It can be named anything, but `styles.css` or `style.css` is standard
- How to link to your CSS stylesheet from your `html` file:
    ```html
    <link href="styles.css" rel="stylesheet">
    ```

### `Ruleset` (or rule)

-  A [selector](#selector) with it's [properties](#property) between `{}`

<img src="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png" alt="Mozilla CSS Ex">

#### `Selector`

- Determines which `html` element(s) are styled
    - In this case, `p` is the selector
    ```css
    p {
        color: red;
    }
    ```

#### `Property`

- Determines which part of the way the selected `html` will be changed
    - In this example, `color` is the property
    ```css
    p {
        color: red;
    }
    ```

#### `Property Value`

- The way that the property should be changed
    - It is similar to the values of attributes
    - In this example, `red` is the property value
    ```css
    p {
        color: red;
    }
    ```

### `Declaration`

- A property and it's value.
    ```css
    color: red;
    ```

#### `Curly Braces`

- The `{}` that begin after the selector and end the property declarations.

#### `Colon`

- The `:` that comes after the property name.

#### `Semicolon`

- The `;` that ends a [declaration](#declaration) after a property value.
    ```css
    p {
        color: red;
    }
    ```

### `Multiple Properties`

```css
p {
  color: red;
  width: 500px;
  border: 1px solid black;
}
```

### `Multiple Selectors`

- The following example turns all `p`, `li`, and `h1` elements red
    ```css
    p, li, h1 {
      color: red;
    }
    ```
