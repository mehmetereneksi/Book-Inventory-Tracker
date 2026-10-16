# Book Inventory Tracker 📚

A clean, visually appealing book inventory and tracking interface built entirely with pure HTML and CSS. This project utilizes semantic HTML tables and advanced CSS selectors to create dynamic status badges and a custom CSS-only rating system.

## ✨ Features

- **Semantic HTML Table:** Data is neatly organized using properly structured `<table>`, `<thead>`, and `<tbody>` tags.
- **Dynamic Status Badges:** Reading statuses (*Read, To Read, In Progress*) are styled as pill-shaped badges with distinct borders and colors.
- **CSS-Only Rating System:** A unique visual rating system created using CSS Flexbox and borders. The rating circles are filled dynamically using advanced CSS attribute selectors (`[class^="rate"]`, `[class~="one"]`) and pseudo-classes (`:first-child`, `:nth-child`).
- **Color-Coded Rows:** Each table row features a smooth linear gradient background that corresponds to the book's current reading status, enhancing visual hierarchy and user experience.

## 🚀 Demo

[Live Demo](https://mehmetereneksi.github.io/Book-Inventory-Tracker/)

## 🛠️ Technologies Used

- **HTML5:** Semantic table structuring.
- **CSS3:** Flexbox, Linear Gradients, Attribute Selectors, and Pseudo-classes.

## 📁 Project Structure

```text
├── index.html    # Main document containing the table structure and book data
└── styles.css    # Stylesheet for custom gradients, layout, and rating logic
```
