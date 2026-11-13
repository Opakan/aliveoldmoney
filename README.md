# ALIVE OLD MONEY — "OWN THE MACHINE" LANDING PAGE
**Domain:** [aliveoldmoney.shop](https://aliveoldmoney.shop)  
**Product:** Complete 2026 Operator Edition: *"OWN THE MACHINE: Stop Working for Money—How to Fix Your Finances, Acquire Cash-Flow Assets, and Scale a Company"* (48-Page Fact-Checked Manual + 12 Deal Templates).

---

## ⚡ Instant 5-Second Gumroad Product URL Setup

The checkout link is centralized in a single constant at the top of `index.html`:

```html
<script>
  const GUMROAD_CHECKOUT_URL = "https://gumroad.com/l/own-the-machine";
</script>
```

When you update this single constant, every CTA button across the page (Hero, Sticky Header, Facebook Lookup Grid, Story Contrast, DSCR Calculator, Value Stack, and the Sticky Mobile Bottom Bar) automatically syncs.

Gumroad's official overlay script is embedded:
```html
<script src="https://gumroad.com/js/gumroad.js"></script>
```
When a prospect taps any CTA button, Gumroad's modal checkout overlay opens directly on top of your page—maximizing mobile conversion rates by preventing in-app browser redirect drops.

---

## 🚀 1-Click Free Deployment to Vercel

This project uses a zero-build-error, ultra-high-speed static architecture (Semantic HTML5 + Tailwind CSS + Lucide Icons + Vanilla JS). It requires **zero npm dependencies**, compiles with **zero build errors**, and loads in under 200ms on Facebook mobile in-app browsers.

### Option A: 1-Click Deployment via GitHub (Recommended)
1. Push this folder to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Alive Old Money landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/aliveoldmoney.git
   git push -u origin main
   ```
2. Log into [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your `aliveoldmoney` GitHub repository.
4. Leave all build settings at default (`Framework Preset: Other`, `Build Command: None`, `Output Directory: None`).
5. Click **"Deploy"**. Your site is live on Vercel's global edge network in ~5 seconds.

### Option B: Deploy via Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 🌐 Connecting Your Custom Domain (`aliveoldmoney.shop`)

1. Go to your Vercel Project Dashboard → **Settings** → **Domains**.
2. Enter `aliveoldmoney.shop` and `www.aliveoldmoney.shop`.
3. Configure your DNS records at your domain registrar (Namecheap, GoDaddy, Cloudflare, etc.):
   - **A Record:** `@` points to `76.76.21.21`
   - **CNAME Record:** `www` points to `cname.vercel-dns.com`
4. Vercel will automatically provision free SSL certificates and activate your site.

---

## 🎨 Design System & Direct-Response Psychology

- **Aesthetic:** "Institutional Old Money meets Wall Street Private Equity" (Berkshire Hathaway, Morgan Housel, Wall Street Journal).
- **Color Palette:**
  - Obsidian Navy (`#0A0F1D`) & Rich Charcoal (`#111827`)
  - Warm Parchment Cream (`#F9F6F0`) for "Inside the Pages" sections to simulate genuine bond paper.
  - Brushed Champagne Gold (`#D4AF37`) for accents, badges, and financial metrics.
  - Emerald Wealth Green (`#10B981`) for high-converting CTA buttons with subtle pulsing glow.
- **Typography:**
  - *Playfair Display* / *Cinzel* for authoritative editorial headlines.
  - *Inter* for legible body copy.
  - *JetBrains Mono* for formulas, page citations, and financial tables.
- **Mobile First (92% Facebook Traffic):**
  - Sticky announcement bar at top with 50% discount callout.
  - Sticky mobile bottom CTA bar that slides up after scrolling 300px.
  - Touch targets calibrated to ≥48px height.
  - Safe area insets (`env(safe-area-inset-bottom)`) for modern iPhones/Android devices.
- **Interactive Conversion Widgets:**
  - **CSS 3D Book Mockup:** Realistic hardcover depth with gold foil embossing, paper edge ridges, and hover tilt.
  - **Facebook Video Lookup Grid:** 6 cards with exact page and asset citations (Pages 6–8, 10–14, 16–18, 24–25, 27–31, 35–44) with interactive parchment preview modals.
  - **30-Minute Underwriting Napkin Calculator:** Real-time DSCR calculation checking against the book's 1.50x Operator Cushion Rule.
  - **Social Proof Toast:** Discreet rotating notifications showing recent downloads from real operator locations.

---

## 📁 Repository Structure

```
├── index.html       # The complete, self-contained landing page
├── vercel.json      # Production Vercel config with security headers & clean URLs
├── robots.txt       # Search engine crawler permissions
├── sitemap.xml      # XML sitemap for aliveoldmoney.shop
└── README.md        # Deployment and configuration guide
```

---

## ⚖️ Legal & Copyright
© 2026 Alive Old Money — [aliveoldmoney.shop](https://aliveoldmoney.shop). All rights reserved.  
Contains the official Legal, Financial & Tax Disclaimer from Page 1 of the book.

