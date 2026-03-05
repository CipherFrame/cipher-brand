# CipherFrame Style Guide
**A unified GitHub-first brand system for CipherFrame repos.**  
**Vibe:** *dark Batman cave + renegade hacker poster* (NOT corporate).

---

## 0) Prime Directive
If it looks like it belongs on an enterprise vendor website, **it’s wrong**.

CipherFrame should feel like:
- **Black-site tooling**
- **Trap-first / alarm-first**
- **Poster energy**
- **Minimal elements, maximum punch**
- **Thick type, high contrast**
- **Dark “batcave” atmosphere** (deep blacks + controlled red/yellow heat)

---

## 1) Brand DNA
### Archetype
**Renegade / Trap-first / “touch the wrong thing.”**

### Mood keywords
**dark, kinetic, menacing, confident, sparse, loud, industrial**

### Visual metaphors
- **Tripwire / laser grid**
- **Alarm glow / warning signage**
- **Bait / decoy / wrong folder**
- **Impact / scorch / slash**

### Hard rules (non-negotiable)
- **NO corporate blue gradients**
- **NO glossy glass UI panels**
- **NO generic lock/shield stock icons**
- **NO cluttered icon salad**
- **TITLE TEXT IS THE HERO**

---

## 2) Color System (batcave palette)
Use these exact hex values everywhere.

### Core palette
- **Cipher Black (base):** `#0A0A0C`
- **Cipher Void (deeper):** `#050507`
- **Cipher Smoke (panel):** `#15151B`
- **Cipher Red (heat):** `#FF2A2A`
- **Cipher Yellow (hazard):** `#FFD400`
- **Cipher White (text):** `#F2F2F2`
- **Cipher Ash (muted):** `#B6B6B6`

### Usage rules
- Canvas is **90% black** (Void + Black).
- **CIPHER** word is **red**.
- Project noun (**EDR / OSINT / etc**) is **yellow**.
- Secondary text is **white/ash only**.
- Red/yellow are **sparks**, not wallpaper: use them for **impact zones** and **type**.

---

## 3) Typography (THICCCCC)
### Title font direction (choose ONE and stick to it)
- **Anton**
- **Bebas Neue**
- **Impact** (clean, brutal, intentional)
- **Druk Condensed** (if you have it)

### Title rules
- Prefer **ALL CAPS**.
- **Huge** title. Heavy weight. Slightly condensed.
- Tight tracking (don’t space it out).
- Optional: **hard shadow** or **outline** (subtle, not cartoony).
- Optional: **distress/grit** on type (poster print texture), but keep readability.

### Naming convention (visual)
Always format titles like:
- **CIPHER** (red) + **EDR** (yellow)
- **CIPHER** (red) + **OSINT** (yellow)
- **CIPHER** (red) + **HUNTKIT** (yellow)

**Rule:** the noun (EDR/OSINT/…) should be **as big or bigger** than “Cipher”.

---

## 4) The “Batman Cave Poster” Look (the style in your samples)
This is the house style for README banners and social previews.

### Composition
- **Big text dominates** (poster/title-card energy).
- **Minimal objects** (0–1 emblem max).
- **Deep black** background with subtle vignette.
- **Controlled chaos**: red/yellow “impact” is concentrated, not everywhere.

### Signature motifs (pick 1–2 max per banner)
- **Diagonal slashes / torn-edge bars** (red/yellow wedges at edges)
- **Grunge splatter** (subtle, like dust + paint flecks)
- **Soft neon glow** behind type (red heat / yellow hazard)
- **Scorch / sparks / ember specks** (tiny, restrained)
- **Faint texture** (film grain, halftone, scanlines—VERY subtle)

### What to avoid
- Busy backgrounds
- Many icons
- Detailed diagrams
- “Tech wallpaper” patterns

---

## 5) Texture & Graphic Language
### Allowed textures
- film grain (subtle)
- vignette (dark corners)
- dust/speckle
- distressed print texture
- scanlines (barely there)
- slash marks / torn bands
- hazard stripe fragments (rare)

### Not allowed
- floating hexagons
- corporate wave curves
- glossy “UI mockup” look
- bright rainbow gradients

---

## 6) Icon / Mark System
### Primary mark
A single **CipherFrame mark** (recommended motif):
**fox / predator / trap / alarm** — angular, aggressive, readable at small sizes.

### Required variants
- 1-color (white)
- 1-color (red)
- 2-color (red/yellow)
- dark-mode default (preferred)

### Rule
Do **not** invent a new logo per repo.  
Same mark. Different noun.

---

## 7) README Header Banner Standard
### Banner spec
- **1600 × 500** (recommended)
- Safe padding: **8–10%**
- Keep title away from edges (mobile cropping)

### Banner content rule
Poster mode:
- Title only (and optionally **one** short tagline)
- **No technical detail** in the banner

### Taglines (choose one, max 5 words)
- **TRAP-FIRST DETECTION**
- **TOUCH THE WRONG THING**
- **DECOYS. TRIPWIRES. DONE**
- **AMBUSH-BASED SECURITY**

---

## 8) Repo Writing Voice (README copy)
### Tone
Short. Confident. Slightly menacing. No MBA filler.

### Banned phrases
- “enterprise-grade”
- “best-in-class”
- “robust platform”
- “synergy”
- “next-generation” (unless clearly ironic)

### Recommended README structure
1) Banner
2) One-line pitch
3) Why it exists
4) How it works (high-level)
5) Install / Run
6) Roadmap
7) Threat model / assumptions
8) License

---

## 9) Repo Naming Conventions
Repo names: `cipher-edr`, `cipher-osint`, `cipher-huntkit`, etc.  
Display titles: `Cipher EDR`, `Cipher OSINT`, etc.

---

## 10) Standard Asset Pack (source of truth)
Create a repo: **`cipher-brand`**

Suggested structure:
```
/brand
  STYLE_GUIDE.md
  colors.css
  logo-mark.svg
  logo-wordmark.svg
  banner-template-1600x500.png
  social-preview-1280x640.png
/templates
  README_TEMPLATE.md
  SECURITY_TEMPLATE.md
/github-defaults
  ISSUE_TEMPLATE/
  PULL_REQUEST_TEMPLATE.md
  CODE_OF_CONDUCT.md
```

---

## 11) AI Image Prompt Templates (copy/paste)
### A) Repo banner (Batman cave poster mode)
Design a wide GitHub README banner (1600x500) for “Cipher {NOUN}”.
Vibe: dark Batman cave + renegade hacker poster. NOT corporate.
Mostly black background with deep vignette and subtle film grain.
THICC title text: “CIPHER” in blood red, “{NOUN}” in hazard yellow.
Minimal composition: big text dominates, optional small angular emblem.
Add 1–2 motifs only: diagonal slash bars, torn-edge wedges, subtle splatter, ember specks, soft neon glow behind text.
High contrast, simple shapes, clean layout, readable at thumbnail size.

### B) Square avatar / mark
Create a simple, angular CipherFrame icon on near-black.
Accents only in red/yellow. High contrast. Readable at tiny size.
Motif: predator/fox/trap/alarm (no corporate locks/shields).

---

## 12) Consistency Checklist
- [ ] Black/red/yellow palette used correctly
- [ ] “CIPHER” is red; noun is yellow
- [ ] Huge title text dominates
- [ ] Minimal elements (no clutter)
- [ ] Dark batcave mood (vignette + subtle grain)
- [ ] Same mark system across repos
- [ ] README voice is short + confident
