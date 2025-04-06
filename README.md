# 🍱 Shokugeki Recipes

A small HTML-only project inspired by **Shokugeki no Soma** — I recreated a few dishes from the anime as simple recipe pages.

---

## 📝 What’s Included

- `index.html` — homepage that links to all the recipes  
- `recipes/steakdon.html` — Chaliapin Steak Don  
- `recipes/chazuke.html` — Seer Fish Rice Ball Chazuke  
- `recipes/furikake.html` — Furikake Gohan  
- `images/` — folder for all the food images

---

## 💡 What I Practiced

- **Basic HTML structure**: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- **Semantic elements**: Used tags like `<main>`, `<section>`, `<figure>`, `<nav>` for clean, accessible layout
- **Headings**: Structured content clearly using `h1` through `h5`
- **Lists**: Ingredients and steps organized with `ul` and `ol`
- **Links**:  
  - Internal navigation using anchor tags (`<a href="...">`)  
  - "Return to top" links use IDs with `href="#header"`
- **Images**: All images include `alt`, `width`, and `height` for accessibility and layout control
- **Folder structure**:  
  - HTML files are inside a `recipes/` folder  
  - Images live in a top-level `images/` folder  
  - Used `../` to move out of the recipes folder when referencing shared resources

---

## 🧠 Quick Reminders

### 🧱 Layout Structure

- Place all page content inside the `<main>` tag  
- Wrap grouped content (like ingredients or steps) in `<section>`  
- Use `<figure>` for images, especially if you want to caption them later  
- Navigation (like return links) goes in `<nav>`, usually below the main content  

### 🔗 Link Types

- **Relative links**: Use paths like `./recipes/steakdon.html` or `../images/pic.jpg`  
- **Anchor links**: Use `#id` to jump to elements on the same page (`href="#header"`)  
- **External links**: Use full URLs like `https://example.com`  
  - Include `target="_blank"` to open in a new tab  
  - Add `rel="noopener noreferrer"` for security best practices  

```html
<a href="https://example.com" target="_blank" rel="noopener noreferrer">External Site</a>
```

---

## 📚 HTML Basics (Quick Glossary)

### 📦 Elements
An **element** is everything from the opening tag to the closing tag.

```html
<p>This is a paragraph.</p>
```

### 🏷️ Tags

- **Opening tag**: `<h1>`  
- **Closing tag**: `</h1>`  
- **Self-closing tag** (no end tag needed): `<img />`, `<br />`

### 🧩 Attributes

Attributes provide extra information about an element, placed inside the opening tag.

```html
<img src="../images/steakdon.jpg" alt="Steak Don" width="500" height="300" />
```

Common ones include:

- `src` — image source  
- `href` — link destination  
- `alt` — alternative text for images  
- `id` — unique identifier for anchor links  
- `class` — used for styling or grouping  
- `target="_blank"` — opens a link in a new tab  
- `rel="noopener noreferrer"` — security best practice for external links
