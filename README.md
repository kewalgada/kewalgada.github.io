# DNZ Resources — Website

**Live URL:** https://dnzresources.github.io

DNZ Resources FZC · Connect With Paper · Since 1960

---

## What This Is

This is the official website for DNZ Resources — a global paper trading company specialising in second-choice paper, board, pulp and flexible packaging materials. The website is a single HTML file hosted on GitHub Pages at no cost.

---

## Files in This Repository

| File | Purpose |
|------|---------|
| `index.html` | The entire website — all HTML, CSS and JavaScript in one file |
| `logo.png` | DNZ Resources logo used in the nav bar and footer |
| `README.md` | This file |

---

## How to Update the Website

1. Go to [github.com/dnzresources/dnzresources.github.io](https://github.com/dnzresources/dnzresources.github.io)
2. Click `index.html`
3. Click the pencil ✏️ icon to edit
4. Make your changes
5. Click **Commit changes**
6. The site updates within 60 seconds

Or to replace the whole file:
1. Click **Add file** → **Upload files**
2. Drag the new `index.html`
3. Click **Commit changes**

---

## Common Things to Update

**Change contact email or phone**
Search for `eu@dnzresources.ae` or `+49 15751461631` in `index.html` and replace.

**Add a new product to the product list**
Find the `products-wrap` section under `area-paper` or `area-flex` and add:
```html
<span class="product-pill">New Product Name</span>
```
Add `class="product-pill highlight"` if it is a specialisation.

**Change the Formspree contact form endpoint**
Find `YOUR_FORM_ID` in `index.html` and replace with your Formspree form ID.
Sign up free at [formspree.io](https://formspree.io) to get one.

**Update the stats bar numbers**
Find the `.stats-bar` section and change the numbers in `.stat-num`.

**Add a new paper journey stage**
In the JavaScript `stages` array, add a new object following the same pattern as the existing stages.

---

## Technology Stack

| What | How |
|------|-----|
| Hosting | GitHub Pages (free) |
| Domain | github.io subdomain (free) |
| HTML/CSS/JS | Single file, no framework, no build step |
| Fonts | Google Fonts — DM Serif Display, Inter, JetBrains Mono |
| Contact form | Formspree (50 submissions/month free) |
| Logo | PNG file served alongside index.html |

---

## Contact

**Kewal Gada**
eu@dnzresources.ae
+49 15751461631

DNZ Resources GmbH · Cologne, Germany
DNZ Resources FZC · Sharjah, UAE
