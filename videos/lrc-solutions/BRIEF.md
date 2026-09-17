---
workflow: product-launch-video
flow: automation
storyboard: no
message: "LRC IT Solutions is BI, automation and AI, custom-built for manufacturing, restaurants and reception"
destination: website
aspect: 1920x1080
language: it
length: 15s
angle: company-overview
narration: no
style_preset: coral
---

## Intent

REVISION (v2) — the first cut ("Chiaro": stock factory photography resolving
into a dashboard photo, blue-professional preset, single-metaphor, long
static hold on the close) was rejected: too corporate/restrained, felt
"feo", and used generic stock imagery instead of telling the viewer who
the company is. User asked for: no more stock photos; a more fun/modern
graphic look; and to actually cover who LRC is and what it does. User
picked the **Coral** frame preset by eye (bold magazine-poster, solid
color planes at hard edges, tracked uppercase display type) and asked for
it in LRC's own blue instead of coral-red — `build-frame.mjs` already
remixes it onto the brand tokens (`#2563EB` blue + a light `#C3D4F9`
"celeste" tint), so this is a straight preset swap, not a bespoke palette.
User also asked for **more text and more movement** while keeping the
video at 15s — denser, faster-cut, no stock photography anywhere; every
visual is typography/geometry built in the preset's own vocabulary
(solid planes, 45° hatch, wallpaper numerals), not an invented photo.

New structure is a fast company-overview, entirely from the site's own
real copy: who LRC is (BI + automation + AI) → what it does (the mission
line) → who it serves (the three verticals: Agenzia IA, Manifatturiero,
Business & Ristorazione) → sign-off (tagline + wordmark + contact). Four
short hard-cut frames instead of three slower ones, to fit more real
content into the same 15s without feeling rushed-empty.

## Customizations

- No stock/captured photography anywhere in this cut — every frame is
  typography + the Coral preset's own geometric vocabulary (solid color
  regions, hard edges, diagonal hatch, wallpaper numerals).
- No "+24%" stat (still declined) — no invented numerals of any kind,
  per frame.md's own hard rule.
- No narration/voiceover; still silent, but more on-screen text and
  faster cuts/reveals than the first cut.

## Notes

- Style preset: **coral**, remixed onto the brand's blue (`#2563EB`
  primary / `#C3D4F9` light tint) — chosen by the user by eye from a
  rendered comparison of blockframe / capsule / coral.
- Site's own positioning carries the content: BI + automation + AI for
  manufacturing, restaurants, and service businesses; the three named
  verticals are Agenzia IA (AI reception/booking bot), Manifatturiero
  (Traccia quality control), Business & Ristorazione (Tavolo).
- Site copy and target market are Italian; keep on-screen text in Italian.
- Storyboard/sketch review skipped — single confirmed build, autonomous
  mode (flow: automation, storyboard: no).
