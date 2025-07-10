# HTML - Elements of a Web Page

## Description
This project focuses on understanding and using semantic HTML5 to structure a web page.  
No styling or CSS is involved — the purpose is to build a clean, well-structured, and accessible HTML layout using proper tags and document flow.

The project uses a fictional digital agency called **Techium** as the base content for all pages.

## Objectives
By the end of the project, you should be able to:

- Follow HTML5 coding guidelines and structure.
- Create a valid HTML5 document skeleton.
- Understand and apply semantic tags: `header`, `main`, `footer`, `nav`, `section`, `article`, `aside`.
- Use `div` and `span` appropriately.
- Use proper heading levels and maintain hierarchy (`h1` to `h6`).
- Create and structure lists: unordered (`ul`), ordered (`ol`), and definition (`dl`).
- Embed multimedia content: images, video, audio, iframe.
- Structure and present tabular data using `table`, `thead`, `tbody`, `th`, and `td`.
- Use semantic elements like `details`, `summary`, `blockquote`, `address`, etc.

## Structure
The project is structured in incremental files named `X-index.html` (where X is the task number), plus:

- `article.html`
- `about.html`
- `latest_news.html`
- `contact.html`
- `styleguide.html`

## Key Implementations

### HTML Document Setup
- Begins with `<!DOCTYPE html>` and `<html lang="en" dir="ltr">`
- Metadata includes:
  - `<meta charset="utf-8">`
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">`
  - `<meta name="description" content="Techium is a digital agency">`
  - Favicon support (`favicon.ico`, `favicon.png`)

### Page Layout
- Semantic layout with `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Content sections include:
  - Hero
  - Services
  - Works
  - About Us
  - Latest News
  - Testimonials
  - Contact

### Navigation
- Primary navigation in `<nav>` using `<ul><li><a></a></li></ul>`
- Footer includes primary and secondary navigation lists

### Multimedia
- Images added with appropriate `alt`, `width`, and `height` attributes
- Embedded video (looped, with poster and fallback)
- Embedded audio with controls and fallback
- Embedded YouTube video using `iframe`

### Style Guide Demonstrations
Contained in `styleguide.html`:
- Headings from `h1` to `h6`
- Paragraphs and subtitles
- Inline and block quotes
- Address formatting
- Code blocks with `<pre>` and `<code>`
- Lists: unordered, ordered, and definition
- Horizontal rules
- `details` and `summary` toggles
- Embedded media (video, audio, iframe)

### Tables
- Table with movie titles, directors, and release dates
- Use of `scope="row"` and `scope="col"` for accessibility

### Accessibility & Best Practices
- Proper heading structure and semantics
- Use of `alt` attributes for all images
- Use of `cite`, `small`, and other semantic tags

## Notes
- This project focuses on **structure only** — no CSS involved
- SVGs used for social media icons
- Favicons and logo images must be in the project root
- Some HTML files may not pass W3C validation due to instructional constraints

