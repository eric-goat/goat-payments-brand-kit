# GOAT Payments — Design System

A working design system for **GOAT Payments**: brand foundations, color & type
tokens, logo assets, UI kits, and a reusable skill for generating on-brand
interfaces, decks, and field/enterprise collateral.

---

## 1. Company & Product Context

**GOAT Payments** is a white-glove payments partner. The business is built on
**35+ bank relationships**, which lets the team **place merchants that other
processors decline** and **architect outcomes** rather than simply process
transactions. The promise: *the right home for every legitimate deal.*

Two audiences must be served by every asset:

| Audience | Needs |
|---|---|
| **Sophisticated merchants** (enterprise) | Trust, credibility, clarity about approvals, underwriting, and outcomes. |
| **500+ agent field force** | Fast, confident, field-ready collateral — one-pagers, battlecards, pitch decks, email signatures. |

**Positioning pillars** (from the brand kit's core values): **Experience.
Integrity. Options.** GOAT's edge is *optionality* — the breadth of bank
relationships means a "yes" where others say "no."

> **Note on two voices.** The original brand kit (a Slidesgo-based deck) frames
> GOAT around SMB processing and the tagline *"Optimizing payment solutions for
> SMB's."* The current company direction supplied by the team is more
> consultative and enterprise-grade: *white-glove, bank-relationship-driven,
> outcome-architecting, never rate-focused.* **This system leads with the
> current consultative positioning** while preserving the kit's visual identity
> (logo, lime + charcoal palette, Montserrat). When in doubt, write like a
> trusted advisor, not a rate sheet.

---

## 2. Sources

These inputs informed the system. The reader may not have access — they are
documented here in case they do.

- **GitHub brand kit:** `eric-goat/goat-payments-brand-kit`
  → https://github.com/eric-goat/goat-payments-brand-kit
  Contains `style.md`, `.cursorrules`, the brand-guidelines deck, and the logo
  AI file. **Explore this repo further** to build richer GOAT assets — it is the
  canonical brand source.
- **Live website:** **https://goatpayments.com/** — the canonical product
  surface. The marketing-site UI kit recreates its home page (nav, hero,
  stat counters, "What Makes Us Unique," Processing Solutions, Market
  Expertise, testimonials, Let's Talk, footer).
- **Brand Guidelines deck** (`GOAT Payments Brand Guidelines-1.pptx`) — a
  13-slide guideline deck (logo usage, clear space, do/don'ts, color standards,
  typography, email-signature rules). Text + embedded logos and fonts were
  extracted from it; see `uploads/` and `assets/logos/`.
- **Logo source:** `goat-payments-logo-green.ai` (vector master, in the repo;
  could not be imported as binary — request the `.ai`/`.svg` if you need vector).

---

## 3. Content Fundamentals (Voice & Copy)

**Overall vibe:** confident, consultative, and direct. A senior advisor who has
seen every deal type and knows exactly where it belongs. Calm authority — never
hype, never a hard sell, never leading with rates.

**Person & address**
- Speak to the reader as **"you"** / **"your business."**
- Refer to the company as **"we" / "GOAT"** — a partner sitting on your side of
  the table.
- Merchants are **"merchant partners,"** not "customers" or "accounts."

**Tone rules**
- **Outcome-first, not rate-first.** Talk about *placement, approval, and the
  right home for a deal* — not basis points or "lowest rates."
- **Plainspoken confidence.** Short, declarative sentences. Say the hard thing
  simply: *"Others decline it. We place it."*
- **Consultative, not transactional.** "We architect outcomes" > "we process
  payments."
- **No fear-mongering, no jargon dumps.** Underwriting and risk are explained,
  not hidden behind acronyms.

**Casing & mechanics**
- **Headlines:** Title Case or sentence case in Montserrat ExtraBold. Keep them
  tight — 3–7 words.
- **Eyebrows / labels / nav:** UPPERCASE with wide letter-spacing (`0.12em`).
- **Body:** sentence case, generous line height.
- The wordmark is always **"GOAT Payments"** (the "GOAT" set in the logo's
  squared display face; never re-typed in body fonts — use the logo asset).
- Tagline (legacy kit): *"Optimizing payment solutions for SMB's."* Use sparingly
  and only where SMB framing fits; prefer outcome-led lines for enterprise.

**Emoji:** **Not used.** This is a financial, trust-driven brand. No emoji in
product, decks, or collateral.

**Example lines (on-brand)**
- "Built on 35+ bank relationships."
- "We place merchants others decline."
- "We don't process transactions. We architect outcomes."
- "The right home for every legitimate deal."
- "Experience. Integrity. Options."

**Off-brand (avoid)**
- "🚀 Lowest rates guaranteed!!!"
- "Sign up now and save big on processing fees."
- Dense acronym soup, breathless urgency, or anything that reads like a coupon.

---

## 4. Visual Foundations

**Palette.** Two brand colors do the heavy lifting, with a deep navy as a
third, supporting brand color:
- **Lime green `#96C100`** — the signature. Used for CTAs, the "A" peak in the
  logo, accents, icon strokes, data highlights. High-energy but used
  *sparingly* against lots of white and charcoal so it stays special.
- **Charcoal `#474749`** — headings, body text, and dark "authority" sections /
  footers. This is the grounding, trustworthy neutral. Not pure black.
- **Deep navy `#003568`** — a co-primary brand color and the workhorse for
  *structure*. Seen across collateral as: the **masthead / header band** (logo
  lockup + accreditation strip), **table & section headers** ("THE MERCHANT
  PROBLEM" / "THE GOAT SOLUTION"), **iconography**, **headlines**, and **key
  stat figures** ("15,000+", "$6 Billion+"). Reads serious, financial, and
  stable; carries dark panels and authority sections (an alternative to
  charcoal) and pairs with lime green for confident green-on-navy contrast.
  Hover/pressed `#1a4977`. Division of labor: **navy structures and grounds;
  green activates** (CTAs, the logo peak, checkmarks, the bottom action band) —
  charcoal stays for long-form body text.
- **White `#FFFFFF`** — the dominant surface. White space is a feature, not a
  gap.
- Supporting neutral, green + navy scales are derived in `colors_and_type.css`
  (`--green-50…900`, `--blue-50…950`, `--neutral-0…950`). Pressed/hover green is
  `#7ba300`; navy is `#1a4977`.

**Color vibe.** Crisp, clean, optimistic-but-serious. The green reads
"growth / go / approval"; the navy reads "trust / stability / authority."
Imagery (where used) skews **cool and clean** — real photography of business
owners and operations, never warm/grainy filters. Note: the legacy kit's faint
**blue circuit-line decorations** (a template artifact) remain *off-brand as a
decoration style* — the new navy is a flat brand color for surfaces and accents,
not a license to reuse those circuit graphics.

**Typography.**
- **Montserrat** throughout — geometric, modern, trustworthy. **ExtraBold (800)**
  for headings, **Regular (400)** for body, Medium/SemiBold for UI labels.
- The wordmark uses a separate squared display face (**Oligopoly**) baked into
  the logo image — never re-typed.
- Strong hierarchy: big ExtraBold headline → regular lead → calm body. Eyebrows
  in uppercase wide-tracked green.

**Spacing & layout.**
- 4px base grid; section rhythm is generous (**32–64px+** between blocks, per the
  kit's "minimum 32–64px" rule).
- Max content width **1200px** for one-pagers / documents; **~1320px** for wide
  web layouts.
- Clean, single-column or simple multi-column grids. Lots of breathing room.
  Strong left-aligned hierarchy.

**Backgrounds.** Predominantly flat **white** or **charcoal**. No noisy
gradients. A subtle **`#f7f7f7`** wash separates sections. Occasional full-bleed
charcoal panel for emphasis (stats, footer, section dividers). The green icon
"peak" can be used oversized + low-contrast as a watermark on charcoal.

**Corner radii.** Subtle and modern — cards `10–16px`, buttons `8–10px` or
pill for primary CTAs, inputs `8px`. Never sharp 0, never overly bubbly.

**Cards.** White surface, **1px `#e2e2e3` border**, soft low-contrast shadow
(`--shadow-sm`/`--shadow-md`), `16–24px` internal padding. Clean borders +
subtle shadow — exactly per the kit ("subtle shadow, rounded corners, clean
borders"). No colored left-border-accent cards.

**Shadows.** Soft, diffuse, low-opacity (charcoal at 6–12%). Used for lift on
cards, menus, and modals — never hard or dark. Primary green CTAs may carry a
faint green glow (`--shadow-green`) on hover.

**Borders & lines.** Hairline `1px` neutral borders define structure. Dividers
are `#e2e2e3`. On dark surfaces, use `#58585a`.

**Transparency & blur.** Used minimally — a frosted sticky header
(white at ~85% + `backdrop-filter: blur`) is acceptable. Avoid heavy glassmorphism.

**Motion.** Restrained and professional. Fades + short slides
(`200ms`, `--ease-out`). Hover lifts of 1–2px. **No bounces, no playful
overshoot** — this is a trust brand. Buttons darken on hover (`#7ba300`) and
nudge down ~1px on press (no shrink-to-nothing).

**Hover / press states.**
- *Hover:* primary buttons → darker green `#7ba300`; secondary/ghost → subtle
  `#f7f7f7` fill or charcoal border; links → green.
- *Press:* translateY(1px), slightly deeper green; no scale gimmicks.

**Iconography vibe:** simple, modern line icons with green accents (see §5).

---

## 5. Iconography

The brand kit does **not** ship a proprietary icon set — `style.md` only
specifies *"Icons: Simple, modern, green accent color."* Accordingly:

- **System used (substitute, FLAGGED):** **[Lucide](https://lucide.dev)** —
  loaded from CDN. Lucide's clean ~1.75–2px geometric line style matches the
  "simple, modern" brief and pairs well with Montserrat. **This is a substitution**
  — GOAT has no official icon library. If GOAT adopts an official set, swap the
  CDN link and update this section.
- **Usage:** line (stroke) icons, stroke `1.75–2px`, sized `20–24px` in UI.
  Default color charcoal `#474749` or deep navy `#003568` (navy is used for the
  feature-icon row in the one-pager); use brand green `#96C100` for emphasis,
  active state, or a single highlighted icon. Never multicolor.
- **The "A" peak mark** (`assets/logos/goat-icon-green.png` /
  `goat-icon-white.png`) is the brand's own glyph — use it as the favicon, app
  icon, watermark, and loading mark. Green on light, white on dark.
- **Emoji:** never. **Unicode dingbats as icons:** avoid — use Lucide.

To use Lucide in an artifact:
```html
<script src="https://unpkg.com/lucide@latest"></script>
<i data-lucide="shield-check"></i>
<script>lucide.createIcons();</script>
```

---

## 6. Logo Assets

In `assets/logos/` (extracted from the brand-guidelines deck; transparent PNGs):

| File | What | Use on |
|---|---|---|
| `goat-logo-primary.png` | Charcoal "GO_T" + green "A" peak + green "PAYMENTS" | **Light** backgrounds |
| `goat-logo-white.png` | White "GO_T" + green "A" + green "PAYMENTS" | **Dark / charcoal** backgrounds |
| `goat-icon-green.png` | The green "A" peak mark alone | Light backgrounds, favicons, watermarks |
| `goat-icon-white.png` | The white "A" peak mark alone | Dark backgrounds |

**Rules** (from the kit): maintain clear space; never recolor, distort, or
descale disproportionately; never re-type the wordmark in another font; pick the
variant that suits the background. Vector master (`.ai`) lives in the GitHub repo.

---

## 7. Index / Manifest

Root files:
- **`README.md`** — this file (context, voice, visual foundations, iconography).
- **`colors_and_type.css`** — the token layer (colors, type, spacing, radii,
  shadows, motion). Import first in every artifact.
- **`SKILL.md`** — Agent-Skill front-matter wrapper so this system can be used
  as a downloadable Claude skill.
- **`style.md`, `.cursorrules`** — the original brand-kit guidance (imported).

Folders:
- **`assets/logos/`** — logo + icon PNGs (see §6).
- **`preview/`** — design-system preview cards (colors, type, spacing,
  components) shown in the Design System tab.
- **`fonts/`** — self-hosted Montserrat (`.ttf` + `.otf`, weights 100–900 +
  italics), wired via `@font-face` in `colors_and_type.css`.
- **`ui_kits/`** — high-fidelity UI recreations. See each kit's `README.md`.
  - `ui_kits/website/` — faithful recreation of **goatpayments.com** home page.
- **`slides/`** — branded 16:9 slide templates (title, section divider,
  content, stat, quote, closing) on `deck-stage.js`.
- **`uploads/`** — original source files + extracted media.

---

## 8. Substitutions & Open Items

- **Oligopoly** (wordmark display face) — not provided as a usable font file
  (the embedded PPTX fonts are obfuscated). The wordmark is delivered as a
  locked image, so this only matters if you need live "GOAT" display text.
  **Flagged — request the Oligopoly font file if you need it.**
- **Montserrat** — exact brand match, **self-hosted** from the user-supplied
  font files in `/fonts` (no CDN dependency). No substitution.
- **Lucide icons** — substitute for the (non-existent) official icon set.
  **Flagged.**
- **Vector logo** (`.ai`) — could not be imported as binary; PNGs are used.
  Request `.svg`/`.ai` for print or large-scale work.
