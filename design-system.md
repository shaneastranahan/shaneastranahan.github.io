# Portfolio Site Design Brief

## Project
One-page portfolio site for a **freelance web designer and AI consultant**.

## Goal
Make it feel **credible, tasteful, modern, understated, editorial, minimal, and quietly confident**.

It should feel **edited, not generated**.

## Avoid
- generic AI-generated landing page feel
- startup / SaaS / crypto aesthetics
- loud gradients
- glassmorphism
- too many colors
- excessive animation
- cheesy marketing copy
- template-looking layouts
- KPI counters, logo strips, fake social proof, big testimonial blocks
- giant browser mockups or floating UI collages

## Constraint
No public project list or gallery. Recent work is **NDA-bound**. Handle that **honestly and elegantly**.

## Visual Direction
Typography-led restrained editorial minimalism.

Signals:
- taste
- seriousness
- discretion
- competence

## Design System

### Fonts
- Headings: **Cormorant Garamond**
- Body / UI: **Inter**

Rules:
- serif for hero + major headings only
- sans for body, nav, labels, buttons, metadata

### Type Scale
- Hero: `clamp(3rem, 7vw, 5.5rem)`
- H1: `clamp(2rem, 4vw, 3rem)`
- H2: `1.75rem`
- H3: `1.125rem–1.25rem`
- Body large: `1.125rem`
- Body: `1rem`
- Caption: `0.875rem`
- Meta: `0.75rem`

Line heights:
- hero: `~1.0`
- headings: `1.1–1.2`
- body: `1.7`

### Spacing
`4, 8, 12, 16, 24, 32, 48, 64, 96, 128px`

### Widths
- page max: `1200px`
- content max: `1100px`
- reading width: `680px`
- narrow text blocks: `560–620px`

### Radius
- buttons: `8px`
- cards / panels / images: `12px`
- small UI: `6px`

### Colors
```css
:root {
  --bg: #f6f3ee;
  --surface: #fbf9f5;
  --surface-2: #f0ece6;
  --text: #171717;
  --text-soft: #5f5a54;
  --text-faint: #8a837b;
  --border: #d8d1c7;
  --border-strong: #bfb6ab;
  --accent: #4d5a52;
  --accent-soft: #dde3de;
  --button-bg: #1a1a1a;
  --button-text: #f8f6f2;
}
```
Rules:
- warm off-white background
- near-black text
- muted warm secondary text
- one restrained accent family only

## Components

### Buttons
Primary:
- dark background
- light text
- thin border
- 8px radius
- no gradient / gloss / oversized pill styling

Secondary:
- transparent background
- subtle border

Links:
- simple, elegant, subtle underline treatment

### Cards / Panels
- use sparingly
- flat or nearly flat
- light border
- minimal or no shadow
- restrained padding
- architectural, not dashboard-like

### Motion / Hover
Allowed:
- slight color shift
- slight border shift
- `translateY(-1px)` at most

Avoid:
- parallax
- animated gradients
- flashy reveals
- springy motion
- exaggerated transforms

## Layout Principles
- paced editorial composition, not generic section stack
- asymmetrical but controlled
- strong vertical rhythm
- typography does most of the work
- varied widths by content type
- restrained dividers

## Page Structure
1. Hero
2. What I do
3. Selected services
4. Approach
5. NDA / private work note
6. About
7. Contact

## Section Notes
- **Hero:** eyebrow, large serif headline, short supporting paragraph, 1–2 restrained CTAs; no hero mockup
- **What I do:** concise positioning across web design, front-end development, applied AI consulting
- **Selected services:** restrained stacked list or calm panels; likely Web Design, Front-End Development, AI Consulting, optional Content / Information Architecture
- **Approach:** short principles / numbered editorial list; themes: clarity before decoration, restraint as confidence, design + implementation together, AI used for real utility not hype
- **NDA note:** brief, calm, matter-of-fact; no fake anonymized case studies
- **About:** short, focused on judgment, clarity, structure, execution, interdisciplinary fluency
- **Contact:** quiet email-first close; optional fit note for independent professionals, small studios, research-driven orgs, early-stage projects needing care rather than noise

## Copy Style
- concise
- direct
- intelligent
- lightly formal
- calm
- non-salesy
- anti-hype

Avoid phrases like:
- cutting-edge
- supercharge
- innovative solutions
- visionary founders
- AI-powered experiences

## Final Standard
Should feel like:
- a real high-end personal studio site
- a carefully edited typographic composition
- a credible presence for a thoughtful practitioner

Should not feel like:
- a generic AI-generated portfolio
- a startup landing page
- a dressed-up marketing template

