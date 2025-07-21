# 📚 Style Guide — Blog Preview Card

This style guide defines the design system and rules used for the **Blog Preview Card** project.

---

## 🎨 Colors

| Name       | HEX / HSL             | Usage                       |
|------------|-----------------------|-----------------------------|
| Yellow     | `hsl(47, 88%, 63%)`   | Primary background, category label |
| White      | `hsl(0, 0%, 100%)`    | Card background, text on dark |
| Gray 500   | `hsl(0, 0%, 42%)`     | Description text            |
| Gray 950   | `hsl(0, 0%, 7%)`      | Body text, headings         |

---

## 🖋️ Typography

| Property         | Value                          |
|------------------|--------------------------------|
| Base Font        | `'Lato', sans-serif`           |
| Alternative Font | `'Figtree', Arial, sans-serif` |
| Font Weight      | 400–900                        |
| Category Label   | Bold, uppercase look           |
| Description      | Regular, muted color           |
| Author Name      | Bold                           |

---

## 📏 Spacing

| Element         | Spacing                                  |
|-----------------|------------------------------------------|
| Card Padding    | `1rem`                                   |
| Container Padding | Desktop: `3rem`; Tablet: `2rem`; Mobile: `1rem` |
| Border Radius   | `1rem` card, `0.2rem` category label     |
| Gap             | `15px` author info                       |

---

## 🔤 Font Sizes

| Element         | Desktop | Tablet | Mobile |
|-----------------|---------|--------|--------|
| Category Label  | 0.8rem  | 0.75rem | 0.75rem |
| Date            | 0.8rem  | 0.75rem | 0.75rem |
| Title           | 1.2rem  | 1rem    | 0.95rem |
| Description     | 0.9rem  | 0.85rem | 0.8rem |
| Author Name     | 0.87rem | 0.8rem  | 0.8rem |

---

## 🎨 Box Shadow

- Standard: `4px 3px 0px 5px rgba(0, 0, 0, 0.8)`  
- Optional mobile tweak: softer shadow for smaller screens.

---

## 🧩 Layout

| Element | Rules |
|---------|-------|
| `.container` | Max width: 1300px, centered, responsive padding |
| `.blog-preview__card` | Fixed width: 360px, responsive shrink |
| `.blog-preview__details` | Flex column |
| `.blog-preview__author` | Flex row, gap: 15px |

---

## ⚙️ Responsive Breakpoints

| Breakpoint | Rules |
|------------|-------|
| `<= 768px` | Tablet: card max-width 300px, font-size shrink, container padding 2rem |
| `<= 480px` | Mobile: card width 100%, container padding 1rem, avatar size smaller |

---

## 🏷️ Class Naming Convention

BEM (Block, Element, Modifier)

Example:  
- `.blog-preview`  
- `.blog-preview__card`  
- `.blog-preview__image`  
- `.blog-preview__category`  
- `.blog-preview__author`  

---

## 📄 Assets

| Asset | Path |
|-------|------|
| Illustration | `./assets/images/illustration-article.svg` |
| Avatar | `./assets/images/image-avatar.webp` |
| Fonts | `./assets/fonts/Figtree-VariableFont_wght.ttf` |

---

## 📌 Notes

- Keep semantic tags: `<main>`, `<article>`, `<footer>`, `<time>`.
- Always provide descriptive `alt` text for images.
- Use `rem` units for scalable sizing.
- Mobile-first media queries.

---

**✅ This style guide ensures consistency for future improvements and reuse.**

