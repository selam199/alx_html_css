# CSS Basic – ALX Frontend Project

This project introduces the basics of CSS by applying styles to existing HTML documents. It is part of the **ALX HTML & CSS curriculum** and builds on the `html_basic` project by adding design and layout improvements using external stylesheets.

---

## 📁 Project Structure
css_basic/
├── index.html
├── tweets.html
├── base.css
└── styles.css
---

## 📌 Objective

- Link CSS files to HTML documents.
- Separate base styling (`base.css`) from custom styling (`styles.css`).
- Understand how external stylesheets enhance the structure and appearance of web pages.

---

## 🛠 What Was Done

1. Created a new directory: `css_basic`.
2. Copied `index.html` and `tweets.html` from the `html_basic` project.
3. Created:
   - An empty `styles.css` for custom styles.
   - A `base.css` file containing foundational styles.
4. Added the following lines inside the `<head>` tag of both HTML files:

```html
<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
