# Odin Recipes

A basic HTML website built as part of **The Odin Project** curriculum.  

This project demonstrates fundamental HTML and CSS skills, including creating pages, linking between them, using lists and images, and styling content.

---

## Live Preview

*(Optional: Add GitHub Pages link here later)*  
[View Live Website](https://yourusername.github.io/your-repo-name/)

---

## Built With

- **HTML5**  
- **CSS3**  

---

## Features

- Multiple HTML pages linked together with relative paths  
- Organized folder structure for CSS and HTML files  
- Ordered and unordered lists for recipes and ingredients  
- Images embedded on recipe pages  
- Page-specific background colors using `<body>` classes  
- Styled links with hover effects, font-size adjustments, and no underline  

---

## What I Learned

- Structuring a basic HTML document correctly  
- Linking pages using relative paths (`href`)  
- Organizing files into folders for easier maintenance  
- Creating ordered and unordered lists for content  
- Inserting and displaying images in HTML  
- Linking CSS files using correct `rel="stylesheet"` and `href` paths  
- Applying page-specific background colors via `<body>` classes  
- Styling links with hover effects and font sizes  
- Debugging CSS issues when pages reside in different folders  

---

## Challenges Encountered

- Background colors only applied to `index.html` initially  
- Recipe pages didn’t apply CSS because `<link>` tags had incorrect paths  
- `<body>` elements missing correct classes for CSS selectors  
- Confusion with relative paths (`../`) for linking CSS and HTML files between folders  
- Hover effects on links were not visible when underline was removed  

---

## Solutions Implemented

- Fixed all `<link>` tags in recipe pages:

```html
<link rel="stylesheet" href="../styles.css">

- Added proper classes to `<body>` elements for page-specific styling:

```html
<body class="recipe-page">

.recipe-page a {
  font-size: 18px;
  color: black;           /* default text color */
  text-decoration: none;  /* remove underline */
}

.recipe-page a:hover {
  color: red;             /* hover color */
}
