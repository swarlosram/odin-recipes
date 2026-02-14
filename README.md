# Odin Recipes

A basic HTML website built as part of The Odin Project curriculum.

This project demonstrates fundamental HTML skills including:
- Creating pages
- Linking between pages
- Using lists
- Adding images
- Structuring content properly
- Adding CSS styling and page-specific backgrounds

## Live Preview

(Optional: Add GitHub Pages link here later)

## Built With

- HTML5
- CSS3

## What I Learned

- How to structure a basic HTML document
- How to create relative links between pages
- How to organize files into folders
- How to use lists (ordered and unordered)
- How to insert and display images
- How to link CSS files correctly using `rel="stylesheet"` and `href` paths
- How to apply page-specific background colors using `<body>` classes
- How to debug CSS issues when pages are in different folders

## Challenges Encountered

- Background colors only worked on `index.html` initially
- Recipe pages didn’t apply CSS because the `<link>` tag had incorrect syntax
- `<body>` elements were missing the correct classes for CSS selectors
- Understanding relative paths (`../`) for linking CSS and HTML files between folders

## Solutions Implemented

- Fixed `<link>` tags in all recipe pages:

```html
<link rel="stylesheet" href="../styles.css">
