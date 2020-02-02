# Typography style set

**Css styling set for blog posts**

### Take a look at the **[demo](http://danjsef.github.io)** for preview.

## Dependencies

This style set requires **[normalize.css](https://necolas.github.io/normalize.css/)** to work properly.

## Implementation

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <!-- load normalize.css first -->
    <link rel="stylesheet" href="normalize.css" />
    <!-- load typography.css second -->
    <link rel="stylesheet" href="typography.css" />
  </head>
</html>
```

## Usage

This library is based on html structure, so you don't have to worry about any classes.

Entire blog post has to be wrapped in **article** tag.

```html
<article>
  <h1>First level heading</h1>
  <p>
    Lorem ipsum
  </p>
  <h2>Second level heading</h2>
  <p>
    Lorem ipsum
  </p>
</article>
```

## Components

### Header

```html
<header>
  <h1>Article heading</h1>
  <div>By <a href="#">Jon Doe</a></div>
</header>
```

### Headings

```html
<h1>First level heading</h1>
<h2>Second level heading</h2>
<h3>Third level heading</h3>
```

### Paragraph

```html
<p>
  Some kind of text.
</p>
```

### Blockquote

```html
<blockquote cite="#">
  Text of the quote.
</blockquote>
```

### Image with caption

```html
<figure>
  <img src="" alt="" />
  <figcaption>
    Caption
  </figcaption>
</figure>
```

### Lists

```html
<ol>
  <li>Lorem</li>
  <li>
    Lorem
    <ol>
      <li>Sub-Lorem</li>
    </ol>
  </li>
</ol>
<ul>
  <li>Lorem</li>
  <li>
    Lorem
    <ul>
      <li>Sub-Lorem</li>
    </ul>
  </li>
</ul>
```

### Footer

```html
<footer>
  <div>
    <img src="" alt="author" />
    <div>
      by <a href="#">Jon Doe</a> <br />
      on xx.xx.xxxx
    </div>
  </div>
</footer>
```
