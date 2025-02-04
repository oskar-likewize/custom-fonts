# Custom Fonts for GitHub Pages

This repository hosts custom fonts for use in web projects. The fonts are stored as `.woff` files and linked via a `font-face.css` file.

## 📌 How to Use

### 1️⃣ Host Fonts on GitHub Pages
1. Upload your `.woff` font files to this repository (inside a `/fonts` directory).
2. Create a `font-face.css` file to define your fonts.
3. Enable **GitHub Pages** under **Settings > Pages**, setting the source to `main`.

### 2️⃣ Add Fonts to Your Website
To use the fonts in your project, link to `font-face.css` in your HTML or CSS:

```html
<link rel="stylesheet" href="https://oskar-likewize.github.io/custom-fonts/font-face.css">
```

or in CSS:

```css
@import url("https://oskar-likewize.github.io/custom-fonts/font-face.css");
```

### 3️⃣ Example `font-face.css`
```css
@font-face {
    font-family: 'CustomFont';
    src: url('https://oskar-likewize.github.io/custom-fonts/fonts/custom-font.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
```

## 🚀 Troubleshooting
- Ensure **GitHub Pages** is enabled under **Settings > Pages**.
- Use the **correct URL** structure: `https://yourusername.github.io/custom-fonts/fonts/font.woff`.
- Try **forcing a refresh** by making a small commit if changes don’t appear.

---
🛠️ **Created by Oskar for hosting custom fonts on GitHub Pages.**
