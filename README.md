# :dog: :cat: Petbook

This project is a social network fot pets! :laughing: :laughing:

But I created only the feed page because it will not be used for anyone, since it's only for study purposes.

## :full_moon_with_face: Motivation

This project was created to study these things:

- CSS BEM convention (Block Element Modifier)
- Semantic HTML
- SEO (meta tags)
- Accessibility in the web

## :rocket: What I Learned

### 1. CSS BEM

BEM (Block Element Modifier) is a very simple methodology that allows you to write more maintainable, consistent and structured CSS styles.

So how to write in a BEM way?

1. BLOCK - Standalone entity that is meaningful on its own
2. ELEMENT - A part of a block that has no standalone meaning and is semantically tied to its block.
3. MODIFIER - A flag on a block or element. Use them to change appearance or behavior.

Example:

```html
<!-- This is the BLOCK -->
<nav class="navbar">
  <!-- This is an ELEMENT -->
  <div class="navbar__links">
    <!-- This is an ELEMENT -->
    <a class="navbar__link" href="#">Link 1</a>
    <!-- This is an ELEMENT with a MODIFIER that changes its color -->
    <a class="navbar__link navbar__link--color-primary" href="#">Link 2</a>
  </div>
</nav>
```

**Tips**

- Don't use HTML tags and IDs in CSS, only classes
- Don't write inline styles in HTML elements
- Use single dashes when you need more than one word in a block, element or modifier. Ex: `navbar__link-icon`

Learn more about BEM on the [Official Website](http://getbem.com/introduction/)

### 2. Semantic HTML

A semantic element clearly describes its meaning to both the browser and the developer.

Why to write semantic HTML:

**1. SEO:** Search Engines can be able to understand the meaning of the content.
**2. Accessibility:** Screen readers can be able to understand the meaning of the content.
**3. Maintainability:** Developers can understand easily the structure of the page.

**Examples of non-semantic elements:**
`<div>` and `<span>` - Tells nothing about its content.

**Examples of semantic elements:**
`<form>`, `<table>`, and `<article>` - Clearly defines its content.

Learn more about in the [W3Schools Website](https://www.w3schools.com/html/html5_semantic_elements.asp)

### 3. SEO

### 4. Accessibility

## :man: Author

Luan Eduardo da Costa | [Add me on Linkedin](https://www.linkedin.com/in/luaneducosta/)
