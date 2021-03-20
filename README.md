# :dog: :cat: Petbook

This project is a social network fot pets! :laughing: :laughing:

But I created only the feed page because it will not be used for anyone, since it's only for study purposes.

:point_right: **[CLICK HERE](https://luanedcosta.github.io/petbook)** :point_left: to see the project working in your browser.

## :full_moon_with_face: Motivation

This project was created to study these things:

- CSS BEM convention (Block Element Modifier)
- Semantic HTML
- SEO (meta tags)
- Accessibility in the web

## :rocket: What I Learned

### 1. CSS BEM

BEM (Block Element Modifier) is a very simple methodology that allows you to write more maintainable, consistent and structured CSS styles.

:thinking: **So how to write it in a BEM way?**

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
See [This Video](https://youtu.be/naha1DIHK4E) to see real examples of semantic HTML

### 3. SEO

SEO (Search Engine Optimization) is the process of improving a website to increase its visibility for relevant searches. With better visibility you gain more attention and could attract new and existing customers to your business.

:thinking: **How to do that?**

**1. Choose a good title for a page**

Put the title into the `title HTML tag`

```html
<title>A Good Title</title>
```

**2. Write a good description in the description meta tag**

```html
<meta name="description" content="A good description" />
```

**3. Use header tags to segment your content**

Headers make it easier for people to find what they're looking for quickly.

- `<h1></h1>` – Usually reserved for webpage titles.
- `<h2></h2>` – Highlights the topic of the title.
- `<h3></h3>` – Reflects points in regards to the topic.
- `<h4></h4>` – Supports points from `<h3>`.
- `<h5></h5>` – Not often used, but great for supporting points of `<h4>`.

**4. Add the alt property in images**

The alt property is used to explain to the search engine what the image is about.

```html
<img src="images/image.png" alt="Explain the image here" />
```

**5. Open graph meta tags**

It helps in boosting search and display abilities for social media.

```html
<meta property="og:locale" content="en_US" />
<meta property="og:site_name" content="My Website Name" />
<meta property="og:description" content="A good description" />
<meta name="og:title" property="og:title" content="The Page Title" />

<meta property="og:image" content="https://www.website.com/images/image.jpg" />
<meta property="og:image:type" content="image/jpeg" />
<meta property="og:image:width" content="800" />
<meta property="og:image:height" content="600" />

<!-- If your website is an article -->
<meta property="og:type" content="article" />
<meta property="article:author" content="Article Author Name" />
<meta property="article:section" content="Article Section" />
<meta property="article:tag" content="Article tags separated by comma" />
<meta property="article:published_time" content="Time" />

<!-- If your website is a normal website -->
<meta property="og:type" content="website" />
```

**6. Responsive site meta tags**

It's crucial to have a mobile-friendly because Google puts emphasis on that and probably many people will use a mobile search to find your website.

```html
<meta name="viewport" content="width=device-width, initial-scale=1" />
```

**7. Twitter card tags**

Open graph isn't the only way to customize data for social media. Twitter has its own platform called "Cards".

```html
<meta name="twitter:card" content="summary" />
<meta name="twitter:title" content="A nice title" />
<meta name="twitter:description" content="200 character description" />
<meta name="twitter:url" content="https://www.yourdomain.com" />
<meta name="twitter:image" content="https://www.yourdomain.com/image.jpg" />
```

Learn more about in these websites:

- [The 10 Most Important HTML Tags You Need to Know for SEO](https://www.greengeeks.com/blog/html-tags-for-seo/)
- [What You Need to Know About Open Graph Meta Tags for Total Facebook and Twitter Mastery](https://neilpatel.com/blog/open-graph-meta-tags/)

### 4. Accessibility

---

## :man: Author

Luan Eduardo da Costa | [Add me on Linkedin](https://www.linkedin.com/in/luaneducosta/)
