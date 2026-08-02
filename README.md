# Skyline Coffee Roasters — Landing Page

A professional landing page for **Skyline Coffee Roasters**, built by [Groundsite](https://groundsite.za).

---

## 📁 File Structure

| File | Description |
|---|---|
| `index.html` | Main landing page — the entire site |
| `skyline-logo.png` | Skyline Coffee Co. logo |
| `skyline-hero.jpg` | Hero section portrait photo |
| `skyline-c1-choc-cake.jpg` | Carousel image 1 |
| `skyline-c2-breakfast-wrap.jpg` | Carousel image 2 |
| `skyline-c3-choc-drink.jpg` | Carousel image 3 |
| `skyline-c4-frappe.jpg` | Carousel image 4 |
| `skyline-c5-coconut-cake.jpg` | Carousel image 5 |
| `skyline-c6-chicken-wrap.jpg` | Carousel image 6 |
| `skyline-c7-crepes.jpg` | Carousel image 7 |
| `skyline-c8-smoothies.jpg` | Carousel image 8 |
| `skyline-c9-toast-coffee.jpg` | Carousel image 9 |
| `skyline-c10-croissant-latte.jpg` | Carousel image 10 |
| `skyline-c11-award.jpg` | Battle of the Beans 2025 award |
| `skyline-c12-storefront.jpg` | Durban North storefront |
| `skyline-c13-menu-board.jpg` | In-store menu board |
| `skyline-c14-gordon-rd.jpg` | Gordon Road location exterior |
| `skyline-c15-interior.jpg` | Interior counter shot |
| `skyline-c16-cups.jpg` | Skyline branded cups |
| `menu.pdf` | *(Add when available)* Full menu PDF |

---

## 🌐 Live Site

Hosted on GitHub Pages:
```
https://yourusername.github.io/skyline-coffee
```

---

## ✏️ How to Make Changes

Open `index.html` in VS Code and press `Ctrl+F`, then search for `CLIENT:` to jump to every editable section.

### Common edits

**Update phone number**
Search `CLIENT:` → find phone references → update `082 444 2492` to the new number

**Update trading hours**
Search `hours-row` → find the hours table → update each row

**Add a carousel image**
1. Name your new photo clearly e.g. `skyline-new-item.jpg`
2. Upload it to this GitHub repository
3. In `index.html`, find `ADD MORE SLIDES ABOVE THIS LINE`
4. Paste this block above it:
```html
<div class="carousel-slide" style="min-width:calc(100%/3.2);aspect-ratio:1;overflow:hidden;flex-shrink:0;padding:0 3px;">
  <img src="skyline-new-item.jpg" alt="Description" style="width:100%;height:100%;object-fit:cover;border-radius:4px;display:block;" />
</div>
```

**Add the menu PDF**
1. Save the menu as exactly `menu.pdf`
2. Upload it to this repository
3. The View Menu button will work automatically — no code change needed

**Connect a custom domain**
See the Groundsite client delivery guide for full DNS connection steps.

---

## 🗺️ Locations

| Location | Address |
|---|---|
| Durban North Café | 28 Mackeurtan Ave, Durban North, 4051 |
| Durban Café | 155 Gordon Road, Durban, 4001 |

**Phone:** 082 444 2492
**Instagram:** [@skylinecoffeeza](https://instagram.com/skylinecoffeeza)
**Uber Eats:** [Order here](https://www.ubereats.com/za/store/skyline-coffee-roasters-durban-north/aEjYwmZ9U_6mq0mziq_EkQ)

---

## 🏆 Awards

- **Battle of the Beans 2025** — Top 3 Best Coffee Shops, Durban North / Glenashley / La Lucia

---

## 🛠️ Built With

- Plain HTML, CSS, JavaScript — no frameworks, no dependencies
- Hosted free on GitHub Pages
- Built by **Groundsite** · groundsite.za

---

*© 2026 Skyline Coffee Roasters. Site by Groundsite.*
