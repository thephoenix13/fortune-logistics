# Fortune Logistics — Design Reference

## Brand Colors
- **Orange:** `#F47920` — primary CTA, warmth, action
- **Blue:** `#00AEEF` — accent, trust, corporate
- **Dark:** `#111827` — backgrounds, navs, dark sections
- **Light BG:** `#F8FAFC` — stats rows, light sections
- **Body text:** `#374151` / `#4B5563`

## Typography
- **Headlines:** `DM Serif Display` (italic, display weight)
- **Body / UI:** `Inter` (weights 300–900)

---

## Design Themes

### A — Bold Command
- **Hero:** Split layout — white left panel + image right with diagonal clip-path cutout
- **Leading color:** Orange (`#F47920`) — stats numbers, CTA buttons, accents
- **Blue role:** Headlines `<em>` tags, trust chips only
- **Float card position:** Bottom-left
- **Feel:** Authoritative, high-contrast, warm, dominant

### B — Diagonal Edge
- **Hero:** Same split + diagonal clip structure as A
- **Leading color:** Blue (`#00AEEF`) — stats numbers, nav border (3px bottom), accents
- **Orange role:** CTA buttons only
- **Float card position:** Bottom-right
- **Feel:** Corporate, tech-forward, cooler tone

### C — Meridian Light
- **Hero:** Full-bleed dark image with gradient overlay (`rgba(17,24,39,.88) → transparent`)
- **Leading color:** Dark + blue accents throughout
- **CTA buttons:** Ghost style (outline), nav CTA is `#111827` dark
- **Trust badges:** Frosted-glass pill style
- **Stats row:** Light background (`#F8FAFC`), dark numbers, blue accents
- **Feel:** Cinematic, editorial, most restrained — cleanest of the three

---

## Pages to Build (all 3 themes × 8 page types)

| # | Page | Slug | Notes |
|---|------|------|-------|
| 1 | Homepage | `/` | ✅ Done — A, B, C built |
| 2 | About Us | `/about` | Company story, leadership, milestones |
| 3 | Services Hub | `/services` | Overview + links to 4 sub-pages |
| 3a | Service Sub-page ×4 | `/services/[slug]` | 4 individual service detail pages |
| 4 | Fleet & Capabilities | `/fleet` | Vehicle types, capacity specs |
| 5 | Industries Served Hub | `/industries` | Overview + links to 4 sub-pages |
| 5a | Industry Sub-page ×4 | `/industries/[slug]` | 4 individual industry pages |
| 6 | Our Network | `/network` | Coverage map, reach, hubs |
| 7 | Why Fortune | `/why-fortune` | Differentiators, trust signals, testimonials |
| 8 | Contact & Quote | `/contact` | Contact form + Request a Quote form |
| 9 | Privacy Policy | `/privacy` | Legal page |

**Total builds:** 3 themes × ~13 pages (incl. sub-pages) = ~39 files

---

## Shared Structure Across All Themes

### Nav
- Logo left, links center/right, CTA button right
- A: Orange CTA | B: Orange CTA | C: Dark (`#111827`) CTA

### Stats Band
- A: Dark band (`#111827`), orange numbers
- B: Dark band, blue numbers
- C: Light band (`#F8FAFC`), dark numbers, blue accents

### Sections / Cards
- All use `border-radius: 10–12px`, subtle shadows
- Section headings: DM Serif Display + Inter subheadings

### Footer
- Dark (`#111827`) background, white text, blue accents across all themes

---

## Build Order Recommendation
1. About Us (simple, no sub-pages — good warm-up)
2. Services Hub + 4 sub-pages
3. Industries Hub + 4 sub-pages
4. Fleet & Capabilities
5. Our Network
6. Why Fortune
7. Contact & Quote
8. Privacy Policy

Build one page fully in A, then adapt for B and C (color swap + hero variant).
