# AG45 Site — Complete Deployment Bundle

**Version:** v1 launch-ready (May 2026)

---

## Quick deployment

1. Back up your current `ag45-site/` folder
2. Replace contents of your site folder with contents of this `ag45-deploy/` folder
3. Hard-refresh browser (Cmd+Shift+R / Ctrl+Shift+R)
4. Test all pages and navigation

---

## Bundle contents

```
ag45-deploy/
├── index.html              ← Homepage
├── bio.html                ← Katherine's full bio
├── board.html              ← The Board (6 members, growth-ready)
├── programs.html           ← Programs deck (12 slides, deep-linkable)
└── programs/
    ├── ownership-blueprint.html
    ├── owners-circle.html
    ├── strategic-cadence.html
    └── leader-run.html

images/
├── 5 Board photos (board-ari, billy, krystle, leighann, nikki)
├── 1 Boardroom hero strip
├── 4 Case study cards (bank, construction, hvac, roofing)
├── 3 Bio timeline photos (Singapore, Australia chiro, Australia family)
└── 2 Katherine portraits (homepage suit, bio gas pump)
```

8 HTML files, 15 images, ~6.5MB.

---

## Locked positioning — what's on the homepage

### Hero
- H1: **Leader Run, Owner Free.**
- Subtitle: *Most owners can't leave. We are the boardroom that builds the asset — sell, transfer, step back, or stay.*

### Hero stats
- 25+ Years operating & advising
- 1,000+ Leaders & owners advised
- 12+ Countries worked across

### Programs section
Opens with the lifelong-momentum thesis: *Real ownership compounds. The programs aren't one-and-done — they're a continuum, designed to build sustainable momentum across years, not weeks. Four altitudes. One methodology. One boardroom...*

### Founder
- Title: Founder & CEO (matches Board page)
- Bio: 25+ years across entrepreneurship, operating, advising, coaching — lived in 4 countries (U.S., U.K., Singapore, Australia), worked across 12+. Architect of True Ownership™. Italicized signature line: *Discernment through chaos and change — and the right people at the table to do something about it.*

### Top navigation
Programs · The Firm · Case Studies · Board · Take the True Owner's Audit (CTA)

### Programs section cards
Each panel has one "Learn more →" button per program, deep-linking to the relevant deck slide.

### Owner's Circle (in beta)
Homepage uses rhythm-free language. Specific cadence (Two 2-hour sessions monthly, 12-month commitment) preserved on deck slide 5 and Owner's Circle program subpage only.

### Phase naming (Ownership Blueprint)
- Phase 1 (Own It) — The owner spine — Map of Me™ — launches summer 2026
- Phase 2 (Build It) — The business spine — systems, structure, operating discipline — launches late 2026

### Leader Run card
"Multi-year engagement + ongoing advisory." Specialist advisors across functional, financial, transactional, and external-relationship specialties.

### Built to Transfer reason card
*Every business should be built to transfer from day one — but few are. By the time the owner is ready to step away, the business often can't run without them. Leader Run™ produces a business that operates without the founder...*

### The Board (6 members)
1. Katherine Breuss — Founder & CEO (featured at top)
2. Leighann Lovely — Sales Advisor
3. Krystle Rogers — Lead Strategist
4. Ari Milner — Technology Advisor
5. Nikki Lee — Brand, Systems & AI Advisor (bio placeholder)
6. Billy Cannestra — SEO Marketing Advisor

Auto-fit grid scales 5 → 15+ members. Group scaffolding ready for category groupings when bench grows past ~10.

### Case study cards
- Roofing: "From founder-dependent to founder-optional."
- HVAC: "Operational tightening + a wealth strategy that holds."
- Construction: "Systems built. Margin discipline installed."
- Bank: "From divided priorities to one direction."

### Programs deck
- 12 slides, hash deep-linkable (`programs.html#slide-3`)
- Slide 4: side-by-side split showing both Phase 1 and Phase 2 with launch dates
- Slide 5 (Owner's Circle): 12-month commitment surfaced

### Bio page
Editorial typography for decade plurals — 1990s and 2000s render with smaller raised "s" so the year reads as primary text.

---

## Pending items (not blockers)

- Nikki Lee's full bio (placeholder shows "Bio in development")
- 5A Framework PDF link (currently `#`)
- Discovery call booking link (currently `mailto:`)
- True Owner's Audit landing refresh
- AG45 logo design
- Client logo marquee (parked)
- "Lived Experience as Credential" reason card still mentions "surviving fraud" (inconsistent with softened founder bio — your call whether to update)

---

## Adding a Board member later

1. Add photo to `images/board-[name].jpg` (800x800)
2. Open `board.html`, copy any existing card block
3. Paste in alphabetical position, update photo/name/title/bio
4. Save and deploy — grid auto-balances

## Switching to category groupings (when Board grows past ~10)

The HTML comment in `board.html` documents the exact pattern. CSS already in place.

## Updating Owner's Circle rhythm later

When the rhythm changes after pilot, only two files need updating:
- `programs.html` (slide 5, slide 6)
- `programs/owners-circle.html`

Homepage stays evergreen.

---

## Brand register
- Colors: Navy `#1A2A44`, Gold `#C9A24B`, Cream `#F9F6EE`
- Fonts: Cormorant Garamond (headlines), Inter (body)
- Voice: Direct, restrained, institutional but warm. Italicized signature lines for emphasis.
