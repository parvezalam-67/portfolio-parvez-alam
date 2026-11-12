# Parvez Alam — Creative Professional Portfolio

> Graphic Designer, Video Editor & Actor · Dhaka, Bangladesh  
> Live Production: Static Single-Page Application (Zero Build Step)  
> Live URL: [https://portfolio-parvez-alam.vercel.app](https://portfolio-parvez-alam.vercel.app)

---

## 1. Overview & Architecture

High-performance, luxury dark brutalist portfolio engineered for maximum speed, visual impact, and full responsive fidelity across mobile, tablet, laptop, and 4K displays.

- **Zero-Build Static Architecture:** Instant deployment to Vercel, Netlify, or any static host.
- **Hardware-Accelerated Canvas Engine:** 120 FPS requestAnimationFrame spotlight with spring-lerp interpolation (`support.js` / DC runtime).
- **Zero-JS Work Filter System:** Pure CSS `:has()` category filtering (`#work:has(#f-video:checked)`).
- **Direct Video Player Controller:** In-place Google Drive & YouTube video modal delegator with custom play button overlays.
- **Responsive Baseline Geometry:** Optical centering and adaptive negative baseline clipping ensuring flawless portrait alignment on both desktop and mobile.

---

## 2. Codebase Structure

```text
Portfolio-Complete/
├── assets/                       # Curated media assets (WebP, JPG, PNG)
│   ├── profile.png               # High-res cutout hero portrait
│   ├── meta-*.jpg                # Production Meta Ads & video thumbnails
│   ├── facebook-reel-*.jpg/png   # Social reel covers
│   └── yt-*.jpg                  # High-res YouTube short film covers
├── vendor/
│   ├── react.js                  # React 18 production UMD runtime
│   └── react-dom.js              # ReactDOM 18 production UMD runtime
├── index.html                    # Unified production document & components
├── support.js                    # Design Component (DC) lifecycle runtime
├── vercel.json                   # Asset caching & clean URLs configuration
└── README.md                     # Engineering documentation
```

---

## 3. Site Sections & Sitemap

1. **Header & Navigation (`#top`):**
   - Sticky blur bar with active section indicator, subline branding, and mobile horizontal swipe-nav (`About`, `Experience`, `Skills`, `Work`, `Acting`, `Contact`).
2. **Hero Section (`#hero`):**
   - Dynamic 120 FPS cursor spotlight, radial dot grid, dual-weight headline, CTA buttons, and optically centered portrait cutout with baseline clipping.
3. **About (`#about`):**
   - Narrative bio, education, languages (IELTS 6.00), and personal interests.
4. **Experience (`#experience`):**
   - Career timeline at Doin.Tech and Strivenith Ventures (CSM Bangladesh).
5. **Skills & Tools (`#skills`):**
   - Interactive software tiles (Photoshop, Illustrator, Premiere Pro, After Effects, Blender, AI tools).
6. **Selected Work (`#work`):**
   - **Featured Videos on Top:** 12 video projects (5 Commercial Video Ads with direct in-place playback + 7 Social Reels).
   - **Analyzed Meta Ads:** High-converting creative campaigns with real ad copy titles.
   - **Motion Graphics & Brand Identity:** Comprehensive creative portfolio.
7. **Acting & Screen Appearances (`#acting`):**
   - Dedicated on-camera performance showcase with 9 cinematic short films:
     1. **Sesh Elan (শেষ এলান):** Heart-touching Islamic short film on repentance and mortality (`NvNa5-fmFVc`)
     2. **Paner Khili (পানের খিলি):** Islamic narrative on sincerity and moral reflection (`wnLosVXNv8I`)
     3. **Bhulpoth (ভুলপথ):** High-impact anti-drug drama on youth vulnerability and redemption (`FD3aJHN1_6I`)
     4. **Kormofol (কর্মফল):** Moral drama exploring divine justice and consequences (`3qyUTCs7pKM`)
     5. **AshaVorosha (আশাভরসা):** Lampost Film Production narrative drama on endurance (`hBKBArA09es`)
     6. **Joutuk 2 (যৌতুক ২):** Hard-hitting social drama confronting dowry exploitation (`2nENNNmSPyg`)
     7. **Songram (সংগ্রাম):** Victory Day special honoring liberation and national pride (`I-pJAsolvqs`)
     8. **Abhiman (অভিমান):** Friendship drama exploring brotherhood and loyalty (`AfxdIF7e9mg`)
     9. **Chintai (ছিনতাই):** Eid special action crime short film on urban courage (`qLaJjZwkgLY`)
   - Each card features one-click inline YouTube playback with fallback direct links to YouTube.
8. **Expertise (`#expertise`):**
   - Core disciplines breakdown and Behance showcase link.
9. **Contact (`#contact`):**
   - Direct email, phone, location, and social links.

---

## 4. Local Preview

Start any local HTTP server in the repository root:

```bash
# Python 3
python -m http.server 8000

# or Node / npx
npx serve .
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 5. Deployment

- **Platform:** Vercel (or Netlify / GitHub Pages)
- **Framework Preset:** `Other`
- **Build Command:** *(Leave empty)*
- **Output Directory:** *(Leave empty)*
- **Production Branch:** `main`
