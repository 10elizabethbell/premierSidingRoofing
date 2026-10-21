# Premier Siding & Roofing Specialist LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/premierSidingRoofing/ · **Repo:** https://github.com/10elizabethbell/premierSidingRoofing · **Built:** 2026-10-21 from Muse brief 2026-10-21 (Facebook groups sweep, thin brief) · **Call Sheet:** site URL set

## Check first
1. **Does (732) 768-5891 take texts?** "Text us", the floating circle and the form all open a text. If it's a landline they fail silently (the header, closing band and form note still offer a call).
2. **The photos are generated, not their jobs.** No visible "example" label (Ellie's no-demo rule); the finish reviewer recommended one. Your call: label them, or swap in real jobs before handing over.
3. **The hero eyebrow "Get it done before winter" is seasonal.** Swap it (e.g. "Siding & roofing") around March.

## What's built
- One page, calm band style: paper header (house mark + "Premier / Siding & Roofing Specialist LLC" wordmark, tap-to-call (732) 768-5891 top right) → photo hero → services on paper → How it works on deep navy → quote form on paper → closing band on navy → footer on deep navy.
- Palette from the flyer's gold-on-black, moved onto navy (no black ground): paper #f4f6fb, navy #17305a, deep #0d1a30, gold #d8ad4c as the fill accent (navy text on it), #7a5810 when gold has to be text on light, blue #1f5aa6 for form hover/focus.
- Hero: a generated photo of a finished blue-siding colonial under a navy overlay (phone crop is the centre of the house). Eyebrow "Get it done before winter", H1 "Siding and roofing, done right." with the letter bounce-in, promise line, buttons "Get a quote" (to the form) and "Text us" (outlined, `sms:`).
- Services: two photo cards (Siding, Roofing) that jump to the form and pre-select the matching chip, a "Not sure what it needs? Ask us." row, and a "Follow us on Facebook" row.
- Quote form (eyebrow "Ask for a quote"): chips (Siding / Roofing / Both / Not sure), name, what's going on, town (optional). The button names the job once one is picked ("Text us about roofing"). Composes a text to (732) 768-5891; a note under it offers a call; after submitting, a fallback offers "Open in Messages", "copy the message" and the number.
- Floating gold text circle: shows after the hero, hides while the form is on screen.
- Close: their flyer line "Our goal is your satisfaction!!" verbatim as the heading, the full LLC name, the big phone number. Footer: name, phone, email (only place it appears), Facebook.
- Favicon / home-screen icon: the flyer logo's house outline redrawn as a simple gold line mark on navy (the flyer's 3D gold logo is unreadable at 16px). og image (`og.jpg`, 1200x630) is the hero with the business name.

## Assumptions I made
- **Email** is `premiersidingllc@outlook.com`: the brief flagged the OCR as garbled, but both the flyer and the Facebook profile picture show it clearly.
- **Tagline** is "Our goal is your satisfaction!!" (the flyer has "is"; the brief's OCR dropped it).
- **The Facebook profile (id 61589703215089) is the business's page:** its profile picture is the business flyer. The page name "Vicente Silva" may be the owner; not used on the site.
- **"We / our" voice**, from the flyer's "Our goal"; crew size unknown.
- **How it works step 2** ("We come and take a look. You get a straight answer and a price.") assumes they quote after seeing the house, which is normal for the trade but not stated. I didn't say "free".
- **Texting works** on (732) 768-5891 (unconfirmed; it's very likely a cell). The number is a `tel:` link in the header and closing band, so calling is always one tap away.
- **Not 40+ audience** (the brief doesn't say), so the default motion is on.

## Placeholders and gaps
- **No place in the H1 and no service area anywhere**, because the brief says not to publish a location. The calm style wants the place in the H1; when the owner names their towns, try "Siding and roofing, done right in <Town>." and add an area line to the closing band.
- **All three photos are generated** (`genimg --local`, Z-Image Turbo via mflux, 2026-10-21), shown only as examples of the service, never captioned as their jobs. Replace with real job photos as soon as the owner sends them.

  | File | Shows | Source |
  |---|---|---|
  | `img/hero-wide.webp`, `img/hero-phone.webp` | Two-story blue-siding colonial, charcoal roof, autumn | generated, seed 11, prompt in `src-assets/gen/run.sh` |
  | `img/siding.webp` | Beige dutch-lap siding, white trim, shrubs | generated, seed 23 |
  | `img/roofing.webp` | Cape Cod dormers, grey shingles, red cedar shakes | generated, seed 37 |
- No work gallery, before/afters or reviews section: none exist. The Facebook row says "Follow us" rather than "See more of our work" because the page only has the flyer.
- No licence number, insurance, years in business, hours or prices on the page.
- The owner's portrait from the flyer isn't used (identity unconfirmed; it also looks AI-edited).

## Questions for the owner
1. Which towns do you cover? (unlocks the H1 place and an area line)
2. Can customers text this number?
3. Photos of real jobs, ideally before/after pairs.
4. Your name, and is the "Vicente Silva" Facebook page yours?
5. Which services beyond siding and roofing (gutters, soffit/fascia, windows, repairs, storm damage)?
6. NJ HIC registration number and insurance (NJ requires the HIC number on ads; worth showing once they give it).
7. Do you give free estimates?
8. Any customer reviews we can quote?

## Ideas not built (yours to pick)
- **Signature motion (opt-in):** runner-up worlds from the trade: (1) siding planks that slide in and lock course by course along the hero's base; (2) shingles laid row by row across the hero as you scroll; (3) autumn leaves blowing off a new roof and gutter; (4) snow settling on a sealed roofline (the "before winter" hook). Best fit: (1), the siding courses, drawn as real lap shadows.
- A services list as rows once the owner confirms more services.
- Before/after slider when real pairs arrive.
- Spanish version (the poster's name suggests it might help; ask first).
- **Impeccable sweep (all modes except live/onboard) + finish review, not applied:**
  - Services cards side by side on phones (cuts ~600px of scroll; less photo presence). Taste call.
  - Non-blocking Cal Sans load, plus waiting up to 700ms for the font before the H1 split so the letters don't reflow mid-bounce.
  - "Example photo" tags on generated photos (see Check first, 2).
  - Remove the footer phone number (it's in view together with the closing band's number); the calm kit keeps it in the footer, so I left it.
  - Token cleanup for the repeated overlay colour.
  - Use the flyer's stars-and-stripes / metallic gold somewhere (e.g. a faint flag texture in the closing band) and the house mark larger in the close.
- **Conflicts with house style, kept on purpose:** Impeccable flags the eyebrow pills (craft floor bans them), the bounce easing on the H1, the floating text circle (duplicate channel) and the diagonal band texture (detector "repeating-gradient stripes", suppressed for `index.html` in `.impeccable/config.json`).

## Not verified
- Real-device touch, and the real SMS handoff on iOS/Android (tested only that the composed `sms:` URL and body decode correctly in Chromium/WebKit).
- Inside Facebook's actual in-app browser.
- Frame rate of the bounce-in on old phones.
