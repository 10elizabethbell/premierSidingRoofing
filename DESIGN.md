---
name: Premier Siding & Roofing Specialist LLC
description: Siding and roofing, done right. A calm phone-first home for a contractor who only had a gold-on-black flyer.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  ink: "#0e1b31"
  body: "#27364a"
  soft: "#4a5868"
  navy: "#17305a"
  deep: "#0d1a30"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c8d3e4"
  gold: "#d8ad4c"
  gold-2: "#e6c272"
  gold-ink: "#7a5810"
  focus: "#1f5aa6"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  phone-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  title-card:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "30px"
    fontWeight: 400
    lineHeight: 1.08
  label-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  field: "10px"
  row: "20px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  stack-sm: "12px"
  stack-md: "16px"
  stack-lg: "20px"
  section: "64px"
  section-wide: "96px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  eyebrow:
    backgroundColor: "rgba(14,27,49,.06)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.12)"
    textColor: "{colors.on-dark}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  service-card:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.card}"
    typography: "{typography.title-card}"
    rounded: "{rounded.card}"
  link-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.row}"
    padding: "14px 16px 14px 22px"
    height: "72px"
  step-marker:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Premier Siding & Roofing Specialist LLC

## Overview

**Creative North Star: "The Flyer's Gold, at Rest"**

The business's only visual asset was a metallic-gold-on-black Facebook flyer. The system keeps the gold and the house-outline mark and moves everything else somewhere calmer: navy instead of black, off-white paper bands between the dark ones, one round display face, and generous phone-first spacing. It should feel like a tidy job site: nothing shouts, every surface has a clear use, and the phone number is always within reach.

The page is a stack of full-bleed bands that alternate light and dark: paper header, photo hero under a navy overlay, paper services, deep-navy steps with a faint diagonal line texture, paper quote form, navy close, deep footer. Gold appears only as a fill (buttons, step numbers, the floating text circle, eyebrow dots) or as the accent phrase in a heading on a dark band. Density is low; one idea per band.

Motion is limited to three things: the hero H1 lands letter by letter with a small overshoot, content below the first screen fades up 12px once, and the floating text circle slides in after the hero. Reduced motion turns all three off.

**Key Characteristics:**
- Alternating paper / navy / deep bands; deep bands carry a 135-degree hairline texture.
- Gold is a fill, never running text; deep gold-ink stands in when gold has to be text on light.
- Cal Sans (400 only) for every heading, button, label and phone number; system sans for running text.
- Pill buttons and chips, 24px cards, 10px fields. No sharp corners anywhere.
- Flat surfaces; depth comes from photo overlays and band contrast. The floating circle is the only shadow.

## Colors

Two navies and an off-white paper, with the flyer's gold as the single warm accent.

### Primary
- **Flyer Gold** (gold): the one fill accent. Primary buttons, numbered step markers, the floating text circle, eyebrow dots, text selection, focus rings on dark grounds, and the accent phrase of headings on dark bands. Text on it is always Harbor Ink.
- **Lamplit Gold** (gold-2): the hover state of Flyer Gold fills. Nothing else.
- **Old Brass** (gold-ink): gold when it has to be text or an icon on a light ground: the header house mark and phone glyph, and the header phone link on hover.

### Secondary
- **Porch Navy** (navy): the closing band and the placeholder ground behind service photos.
- **Night Shingle** (deep): the "how it works" band, the footer and the hero's base colour. Always carries the diagonal line texture when used as a band.

### Tertiary
- **Signal Blue** (focus): focus and hover outlines on light grounds, input/chip hover borders, the text caret. It exists so focus never looks like a gold fill.
- **Brick Red** (error): validation messages and invalid field borders only.

### Neutral
- **Paper** (paper): page ground, header, light bands, theme colour.
- **Card White** (card): the quote form card and the link rows sitting on Paper.
- **Pale Siding** (field): inputs and unselected chips inside the white form card.
- **Harbor Ink** (ink): headings on light, all text on gold, selected chips.
- **Slate Body** (body): running text on light.
- **Weathered Slate** (soft): secondary text on light: ledes, hints, placeholders, the brand subline.
- **Snow on Navy** (on-dark): headings, buttons and links on dark bands.
- **Mist on Navy** (on-dark-soft): running text on dark bands.

### Named Rules
**The Gold Is a Fill Rule.** Flyer Gold is a background, never body or link text on a light ground. Text on gold is Harbor Ink. On light grounds gold becomes Old Brass; on dark grounds Flyer Gold may color a heading's accent phrase.

**The No Black Rule.** The flyer was black; the site never is. The darkest ground is Night Shingle.

**The Two Rings Rule.** Focus is Signal Blue on light grounds and Flyer Gold on dark grounds (hero, navy, deep, footer). A focus ring is never the same color as the fill it surrounds.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system sans (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** a single round, friendly display weight does all the speaking (headings, buttons, form labels, phone numbers), against invisible system text that just reads. Cal Sans is only ever weight 400; hierarchy comes from size, not weight.

### Hierarchy
- **Display** (Cal Sans 400, clamp(42px, 12vw, 80px), 1.02): the hero H1 only, max 11ch, white on the photo. Drops to 52px in short landscape.
- **Headline** (Cal Sans 400, clamp(30px, 7.6vw, 48px), 1.08): section H2s, balanced wrapping. The closing quote runs slightly smaller (clamp(28px, 7vw, 44px), max 16ch).
- **Phone Display** (Cal Sans 400, clamp(30px, 9vw, 52px), 1): the big tap-to-call number in the close band.
- **Title** (Cal Sans 400, 21px, 1.2): step titles, the wordmark; 30px on photo service cards; 18-20px in link rows.
- **Label (display)** (Cal Sans 400, 17px, 1.2): form labels and legends; 18px on buttons.
- **Lede** (system 400, clamp(17px, 4.6vw, 19px)): one line under a section heading, max 38ch; the hero promise is the same voice at up to 20px / 1.5, max 32ch.
- **Body** (system 400, 16px, 1.7): all running text. Inputs are 16px so iOS never zooms.
- **Label** (system 500, 14px, 0.02em): eyebrow pills. The brand subline is system 600 11px, 0.06em, uppercase.

### Named Rules
**The One Weight Rule.** Cal Sans appears at 400 only. Never fake a bold.

**The Accent Phrase Rule.** On dark bands, the last phrase of a heading may take Flyer Gold ("done right.", "works.", "satisfaction!!"). Light-band headings stay Harbor Ink.

## Layout

A single 1160px column (`max-width`, centered) with a 20px gutter on phones and 40px from 760px. Bands are full bleed with 64px vertical padding, 96px from 760px; the hero has its own padding (56/64px phone, 120/136px wide, 40/48px in short landscape). Section heads stack eyebrow, heading and lede with a 16px gap and cap at 640px.

Stacks use a 12 / 16 / 20px rhythm: 12px between buttons and rows on phones, 16px between service cards, 20px inside the form and between cards on wide screens.

Responsive changes are few and deliberate. At 760px: service cards go two-up and flip from 4:5 to 5:4, link rows go two-up, hero buttons sit side by side at 220px minimum, and the hero overlay changes from a vertical to a left-to-right gradient so the photo shows on the right. At 1024px: the quote section becomes a 1fr / 1.2fr grid with a sticky head, the close band puts the phone number beside the quote, and the three steps run in a row. Below 375px the header mark and phone number shrink so the header fits on one line.

## Elevation & Depth

Flat. Surfaces sit on bands, not on shadows; depth comes from photography under navy gradients (the hero and the service cards fade to rgba(9,20,40,.9)) and from the light/dark band alternation. The diagonal hairline texture on Night Shingle gives dark bands a faint material, not depth.

### Shadow Vocabulary
- **Floating lift** (`box-shadow: 0 10px 28px rgba(8,18,36,.32)`): the floating text circle only, because it floats over every band.

### Named Rules
**The One Shadow Rule.** The floating text circle is the only element with a shadow. Cards, rows, buttons and the form are flat at rest and on hover.

## Shapes

Everything is rounded, in three steps: 10px for fields, 24px for cards and the form (20px for the shorter link rows), and full pills for buttons, chips and eyebrows. Circles carry the small round things: step numbers (48px), card arrows (44px) and the floating text circle (60px). Borders are 2px and transparent at rest, so a hover or focus color can appear without a layout shift. Icons are 2.2-2.6px rounded strokes in a 24px box; the house mark is the flyer's logo redrawn in the same stroke.

## Components

### Buttons
Tactile and plain: big pills that say what happens.
- **Shape:** full pill (999px), 56px tall, 26px side padding, optional 20px stroke icon before the label.
- **Primary:** Flyer Gold fill, Harbor Ink Cal Sans 18px label.
- **Hover / Focus:** hover lightens to Lamplit Gold (real pointers only); press scales to 0.98; focus is a 3px ring at 3px offset in the band's ring color.
- **Ghost:** transparent with a 2px Snow on Navy border at 70%, for the secondary action on the photo hero; hover fills white at 10% and the border goes solid.

### Chips
- **Style:** Pale Siding pill, 48px tall, system 16px Harbor Ink, used as the radio set in the quote form.
- **State:** selected fills Harbor Ink with white text; hover shows a 2px Signal Blue border; keyboard focus adds a Signal Blue ring. Service cards pre-select the matching chip.

### Cards / Containers
- **Service card:** a photo card at 24px radius, 4:5 on phones and 5:4 wide, with a bottom navy gradient, a white 30px title and a circular arrow. Hover zooms the photo to 1.04 over 0.6s and fills the arrow gold.
- **Link row:** a white 72px row at 20px radius on Paper, Cal Sans label left and circular arrow right; the arrow fills gold on hover.
- **Form card:** Card White at 24px radius, clamp(20px, 5vw, 32px) padding, 20px internal gap, max 600px. No border, no shadow.

### Inputs / Fields
- **Style:** Pale Siding fill, 2px transparent border, 10px radius, 52px minimum height (120px for the textarea), system 16px Harbor Ink, Weathered Slate placeholder.
- **Focus:** border turns Signal Blue; hover previews the same border.
- **Error:** border and message in Brick Red; the message appears under the field and clears as soon as the user types.

### Navigation
There is no menu. The paper header holds the house mark and wordmark on the left and the tap-to-call number on the right, both at least 44px tall. The footer on Night Shingle lists phone, email and Facebook as 44px Snow on Navy links that turn gold on hover.

### Eyebrow Pill
Ellie's chosen house style (calm-photo style, 2026-10-19), used on the hero and a few section heads, never all of them. A quiet label, not a button: system 14px, a 7px gold dot, ink at 6% (white at 12% on dark), no hover, no arrow, no shadow, never a full gold fill.

### Floating Text Circle
A 60px Flyer Gold circle with the chat icon, fixed bottom right inside the safe area. It slides up after the hero has scrolled away and hides while the quote form is on screen. One circle, never a bottom bar.

### Numbered Steps
Three steps, each led by a 48px gold circle holding the step number in Cal Sans 20px, with a Snow on Navy title and Mist on Navy line. One column on phones, three across from 1024px.

## Do's and Don'ts

### Do:
- **Do** alternate light (Paper) and dark (Porch Navy / Night Shingle) bands, and put the diagonal line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`) on every Night Shingle band.
- **Do** put Harbor Ink on every gold fill, and switch to Old Brass when gold must be text on light.
- **Do** set every heading, button, form label and phone number in Cal Sans 400.
- **Do** keep tap targets at 44px minimum and inputs at 16px.
- **Do** put photos under a navy gradient (rgba(9,20,40,…)) so white type always sits on dark.
- **Do** gate hover styles behind `(hover:hover)` and turn off every animation under reduced motion.

### Don't:
- **Don't** use black grounds; the darkest ground is Night Shingle.
- **Don't** use Flyer Gold for running text or links on Paper.
- **Don't** add shadows to cards, rows, buttons or the form; the floating circle is the only shadow.
- **Don't** style eyebrows like buttons: no hover, arrow, shadow or full gold fill, and not above every heading.
- **Don't** animate anything in the first screen except the hero H1 letters; content already on screen at load never fades in.
- **Don't** add a second floating action or a sticky bottom bar beside the text circle.
- **Don't** use Cal Sans at any weight other than 400.
