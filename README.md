# Fragnarity — Luxury Arabian Fragrances

Official website for **Fragnarity**, a luxury fragrance brand offering authentic Arabian scents.

## 🌐 Live Website

Hosted via GitHub Pages: `https://<your-username>.github.io/fragnarity/`

---

## 📁 Project Structure

```
fragnarity/
├── index.html      ← The entire website (self-contained)
└── README.md       ← This file
```

The site is a **single self-contained HTML file** — all images, styles, and scripts are embedded directly. No build tools, no dependencies, no server needed.

---

## 🚀 How to Deploy on GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main` and folder to `/ (root)`
5. Click **Save**
6. Your site will be live at `https://<your-username>.github.io/fragnarity/` within a minute

---

## ✏️ How to Update Products

All product data is inside `index.html` in the `fragrances` JavaScript array. Each fragrance has:

- `name` — English name
- `arabic` — Arabic name
- `icon` — Emoji fallback
- `tags` — Used for filtering (`"Winter / Autumn"`, `"Summer / Spring"`, `"All Seasons"`, `"feminine"`, `"masculine"`)
- `variants` — Array of `{ label, price, description }` objects
- `season` — Displayed on the card footer

Product images are stored in the `VARIANT_IMAGES` object, keyed as `"fragKey::Variant Label"`.

---

## 📞 Contact

- **WhatsApp:** +961 71 470 722 / +961 81 789 915
- **Email:** fragnarity@gmail.com
- **Instagram:** [@fragnarity](https://www.instagram.com/fragnarity)
- **TikTok:** [@fragnarity.lb](https://www.tiktok.com/@fragnarity.lb)

---

© 2024 Fragnarity — Where luxury meets accessibility.
