---
title: CSS One Pager
description: Willston Web Coding CSS One Pager
---

## CSS

- `CSS` = Cascading Style Sheets
    - This is the _"coding language"_ that helps stylize the look and feel of your `html`
    
- `style.css` = the main css file name that is typically used with `index.html`

- How to link to your CSS stylesheet from your `html` file:

    ```
    <link href="styles/style.css" rel="stylesheet">
    ```

### `Ruleset` (or rule)
-  A [selector](#selector) with it's [properties](#property) between `{}`.

<img src="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png" alt="Mozilla CSS Ex">

#### `Selector`
- In this case `p` is the selector.
    - Which `html` element do you want to style
```
p {
    color: red;
}
```

#### `Property`
- In this example `color` is the property.
    - What property of the `html` element or `selector` do you want to set
```
p {
    color: red;
}
```

#### `Property Value`
- In this example `red` is the property value.
    - What is the value you want to set the property to
```
p {
    color: red;
}
```

### `Declaration`
- A property and it's value.
```
color: red;
```

#### `Curly Braces`
- The `{}` that begin after the selector and end the property declarations.
#### `Colon`
- The `:` that comes after the property name.
#### `Semicolon`
- The `;` that ends a [declaration](#declaration) after a property value.
```
p {
    color: red;
}
```

### `Multiple Properties`
```
p {
  color: red;
  width: 500px;
  border: 1px solid black;
}
```

### `Multiple Selectors`
```
p, li, h1 {
  color: red;
}
```
> To see all valid `CSS` properties , visit
> https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index or search for
> `mozilla css reference` in a search engine

