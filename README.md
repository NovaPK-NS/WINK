# WINK. Curated Experiences

**Website for WINK — Curated Experiences, Halifax, Nova Scotia**

Live site hosted via GitHub Pages.

## 🚀 How to view locally

Just open `index.html` in any browser — no build step, no dependencies.

## 🌐 How to publish on GitHub Pages

1. Push this repository to GitHub
2. Go to your repo → **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/wink-site/`

## 📁 File structure

```
wink-site/
├── index.html      ← The entire website (self-contained)
└── README.md       ← This file
```

## ✏️ How to update content

All content lives inside `index.html`. Open it in any text editor:

- **Experiences** — search for `exp-card` to find each experience block
- **Prices** — search for `From $` to update pricing
- **Contact details** — search for `hello@winkexperiences.ca`
- **Logo** — the logo image is embedded directly in the file (base64)
- **Colors** — all colors are CSS variables at the top of the `<style>` block

## 🔗 Custom domain (optional)

To use `winkexperiences.ca` instead of the GitHub Pages URL:
1. Add a `CNAME` file to this repo containing just your domain: `winkexperiences.ca`
2. Point your domain's DNS to GitHub Pages (see GitHub Pages docs)

---
Built with HTML, CSS & vanilla JavaScript. No frameworks, no dependencies.
