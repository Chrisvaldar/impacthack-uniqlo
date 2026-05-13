# UniqMe

**Winner — Best AI Challenge Idea & Overall Best Idea @ Uniqlo ImpactHack**

---

## What is this?

UniqMe is a personalised outfit curation concept built on top of Uniqlo's existing catalogue. You answer a short quiz about your vibe, colour preferences, fit, lifestyle, height, and build — and it surfaces a curated top and bottom pairing you can browse through a centered outfit carousel.

**This repo is a single HTML file demo.** It was designed, built, and presented in a 2-hour hackathon sprint. There's no backend, no API, no framework — just one self-contained `uniqme.html` file with vanilla JS and a folder of `.avif` product images alongside it.

---

## The idea

Uniqlo makes great clothes for everyone. UniqMe makes them feel like they were made for you.

7 in 10 people struggle to decide what to buy. The problem isn't the clothes — it's the lack of personalisation at the point of discovery. UniqMe sits at that gap: a lightweight quiz that understands your style, fit, and sizing, then presents a shoppable outfit rather than an endless grid.

---

## What's in the demo

- **Style quiz** — vibe, colour palette, fit preference, lifestyle, height (cm/ft with slider), and build
- **Outfit carousel** — centered card carousel showing tops and bottoms simultaneously so you can visualise the full outfit
- **Sizing inputs** — height via typed field or drag slider, CM/FT toggle; build preference to inform fit without asking anything intrusive
- **Save Collection** — a save CTA to signal the end of the curation flow

---

## Running it

No install, no build step.

```
uniqme.html
top1.avif ... top6.avif
bottom1.avif ... bottom6.avif
```

Drop all files in the same folder and open `uniqme.html` in a browser. That's it.

---

## What it isn't

This is a **prototype made for a pitch**, not a production app. It has:
- Hardcoded products (6 tops, 6 bottoms)
- No real recommendation logic — the quiz captures answers but curation is static in this demo
- No authentication, persistence, or backend

The point was to demonstrate the concept and UX flow convincingly in the time available.

---

## Built by

Made for the Uniqlo ImpactHack — 2 hour sprint, one HTML file, zero sleep sacrificed.
