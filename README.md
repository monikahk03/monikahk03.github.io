# Monika Kanekal — Portfolio

Personal portfolio of **Monika Kanekal**, MSc Marketing graduate specialising in consumer insights, GTM strategy, and brand positioning across GCC & MENA markets.

**Live site →** [monikahk03.github.io](https://monikahk03.github.io) &nbsp;·&nbsp; **Repo →** [github.com/monikahk03/monikahk03.github.io](https://github.com/monikahk03/monikahk03.github.io)

---

## Stack

Pure HTML · Vanilla CSS · Vanilla JS — no build step, no dependencies, no frameworks.

All fonts and icons load from CDN (Google Fonts, simple-icons, Iconify). Everything else is a flat file.

---

## File Structure

```
/
├── index.html                          # Entire site — HTML + CSS + JS in one file
│
├── CaseStudy_KcalWorld.jpg             # Case study 01 — Kcal World
├── CaseStudies_Keko (Teaser).mp4       # Case study 02 — Keko (autoplay video)
├── khaltat_bg.mp4                      # Case study 03 — Khaltat (portrait video)
├── CaseStudies_YallaTager.png          # Case study 04 — Yalla Tager logo
│
├── What I Bring_Market Reserach.png    # Phone mockup — Market Research
├── What I Bring_GTM Strategy.png       # Phone mockup — GTM Strategy
├── What I Bring_Brand Intellogence.png # Phone mockup — Brand Intelligence
├── What I Bring_Data and Analytics.png # Phone mockup — Data & Analytics
├── What I Bring_REGIONAL EXPERTISE.png # Phone mockup — Regional Expertise
├── What I Bring_AI Powered Reserach.png # Phone mockup — AI-Powered Research
├── What I Bring_Digital Strategy.png   # Phone mockup — Digital Strategy
└── What I Bring_Competitor Anaylsis.png # Phone mockup — Competitor Analysis
```

> No `node_modules`, no build output, no config files. Just these 13 files.

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, title, availability status, CTA |
| **What I Bring to the Table** | Interactive phone mockup — hover skills to swap image |
| **Case Studies** | Kcal World · Keko (full-bleed split grid with video) |
| **Khaltat #OneLoveManyStories** | Case 03 — portrait video + campaign details side-by-side |
| **Yalla Tager** | Case 04 — scroll-reveal market intelligence cards |
| **Experience** | Work history with role descriptions |
| **Education** | MSc Marketing (Middlesex) · BBA (Dubai) |
| **Certifications** | Grid of professional certifications |
| **Tools & Frameworks** | Categorised tool logos (Analytics · Design · AI · Frameworks) |
| **Contact** | Email (obfuscated) · LinkedIn |

---

## Features

- **Light / Dark mode toggle** — defaults to light; preference saved to `localStorage`
- **Outfit font** — fixed globally via `data-font="outfit"`
- **Cinematic Bento-Box layout** — CSS Grid with full-bleed case study splits
- **Physics-based scroll reveals** — IntersectionObserver with staggered delays
- **Phone mockup interaction** — hover skill items to swap the displayed image
- **Safari autoplay fix** — IntersectionObserver triggers `video.play()` on scroll-in
- **MK favicon** — inline SVG data URI, no external asset needed
- **SEO** — title, meta description, semantic HTML headings

---

## Deployment

### GitHub Pages

1. Push all 13 files to the root of your repository
2. Go to **Settings → Pages → Source → Deploy from branch → main / root**
3. Site will be live at `https://<username>.github.io/<repo-name>`

### Local preview

Just open `index.html` directly in any browser — no server needed.

> **Note:** Videos (`khaltat_bg.mp4`, `CaseStudies_Keko (Teaser).mp4`) must be committed and pushed to the repo. They are served as static assets by GitHub Pages.

---

## Browser Support

| Browser | Status |
|---|---|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari (desktop) | ✅ Full |
| Safari (iOS) | ✅ Videos autoplay via IntersectionObserver fallback |
| Samsung Internet | ✅ Full |

---

*Built with clean, modular HTML/CSS/JS — no frameworks, no build pipeline.