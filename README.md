# Home of Recipes

A simple, responsive recipe website built with plain HTML and CSS. No frameworks, no libraries, no JavaScript — just clean, semantic HTML and external CSS.

---

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with hero, featured dishes, quote and call to action |
| About | `pages/about.html` | Our story and the mission behind the website |
| Recipes | `pages/recipes.html` | Full list of recipes with ingredients and instructions |
| Contact | `pages/contactUs.html` | Contact form for messages and recipe suggestions |

---

## Typography

- **Font:** Roboto (local, variable font)
- **Italic Font:** Roboto Italic (used in quote section)
- Both fonts are loaded via `@font-face` in `styles.css`

---

## Key CSS Concepts Used

- `@font-face` for local fonts
- CSS variables (`--color`, `--font-size`) for consistency
- Flexbox for all layouts (header, hero, cards, CTA)
- `max-width` and `margin: 0 auto` for centering content
- `object-fit: cover` for consistent image sizing
- `:hover` and `:focus` states for interactivity
- Media queries for responsive design at `768px` and `480px`

---

## How to Run

No build tools or setup required. Simply open `index.html` in any browser.

```
Open index.html in your browser
```

If using VS Code, the **Live Server** extension is recommended for a better development experience.