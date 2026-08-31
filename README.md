# ROSHNI — Designer Boutique

Women's luxury couture website (single-page app).  
Private consultations • Custom lehengas, sarees, gowns • Raipur

## Live Features
- Hash-based SPA navigation (Home, Collections, Lookbook, Create Your Look, Custom Design, Gallery, About, Appointment)
- Product filters on Collections page
- Appointment form → opens **WhatsApp** with pre-filled request
- Mobile bottom navigation + responsive design
- All assets included (no external image dependency)

## WhatsApp Config
Already set in `index.html`:

```js
window.ROSHNI_CONFIG = {
  whatsappNumber: "919826675372",  // India country code + number
  instagramUrl: "",
  phone: "9826675372",
  mapsUrl: ""
};
```

Change the number if needed before publishing.

## How to Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `roshni-boutique`).
2. Upload all files from this folder (or push via git):
   - `index.html` (must be at root)
   - `ROSHNI_HERO_REFERENCE.webp`
   - `assets/` folder
3. Go to **Settings → Pages**
4. Source: **Deploy from a branch** → `main` → `/ (root)`
5. Save. Site will be live at:  
   `https://YOUR-USERNAME.github.io/roshni-boutique/`

### Quick Git commands
```bash
git init
git add .
git commit -m "ROSHNI Designer Boutique – complete site with WhatsApp"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/roshni-boutique.git
git push -u origin main
```

## Local Preview
Just open `index.html` in any modern browser, or use a simple server:

```bash
npx serve .
# or
python -m http.server 8000
```

## File Structure
```
├── index.html
├── ROSHNI_HERO_REFERENCE.webp
├── assets/
│   ├── img01.webp … img40.webp
│   ├── icon-*.webp
│   └── bottom-*.webp
└── README.md
```

© 2026 ROSHNI Designer Boutique
