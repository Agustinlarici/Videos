---
format: 1920x1080
duration: 15s
message: "LRC IT Solutions is BI, automation and AI, custom-built for manufacturing, restaurants and reception"
arc: Company overview (compressed) — chi siamo → cosa facciamo → per chi → sign-off
audience: manufacturing, restaurant, and service-business operators (Italian-speaking)
mode: autonomous
music: none
style_preset: coral
---

## Video direction

- **Palette system** (from `frame.md`, never invented): the Coral preset's three-surface system, remixed onto the brand — `{colors.coral}` = brand blue `#2563EB` (both accent AND full environment regions), `{colors.cream-dark}` = the light "celeste" tint `#C3D4F9` the user asked for, `{colors.black}` = near-black `#0F1117`, `{colors.cream}` = white. Headlines: ink on cream/blue, cream on ink — never gray, never white-on-blue (card-icon squares are the one sanctioned white-on-blue chrome per frame.md's own component spec).
- **Motion grammar + reveal model**: REVISION v2 — the first cut held too still and read as corporate/slow. This cut is deliberately **denser and faster**: long-tail `power3` still governs individual entrances (no bounce), but reveals are hard-cut and staggered at a quicker tempo than the first pass, with more elements in motion per frame (kinetic-type escalation, staggered card-assemble, a drawing accent-line) rather than one slow resolve per frame. Silent piece (no VO) — reveals pace to on-screen text cues, spread across each frame rather than dumped at t=0.
- **Rhythm / held-frame allocation**: no frame gets a long static hold this time (that was the v1 complaint). Frame 4 still lands a brief, legible settle at the very end (≤1.2s) so the sign-off can be read — that is the video's only deliberate pause, and even it ends on a small live flourish (the accent-line draw), not dead stillness.
- **Negative list**: NO stock/captured photography anywhere (v1's factory + dashboard photos are fully removed) — every visual is typography + the Coral preset's own geometric vocabulary (solid color regions, hard edges, 45° hatch, wallpaper numerals). No invented stats/percentages (frame.md's hard numerals rule). No gradients except the preset's own rare sanctioned 135° blue feature wash. No rounded rectangles (0-radius per Coral doctrine, circles only). No bouncy/elastic easing, no infinite/looping motion, no lazy breathing.
- **Transitions**: hard, mechanical handoffs to match Coral's "boundary IS the layout" doctrine — `squeeze` and `push-slide` between frames instead of soft crossfades, adding movement at the macro (between-frame) level too.

## Frame 1 — Chi siamo

- scene: Region-Split Cover — a blue top band cycles the three service words fast, then the cream field resolves on the company name
- duration: 3s
- transition_in: cut
- status: animated
- src: compositions/frames/01-chi-siamo.html
- type: hook
- persuasion: Category announcement
- beat: curiosity
- blueprint: kinetic-type-beats (Adapt — Product_Intro: product-intro-kinetic-type-namedrop)
- focal: (typography only — no image asset)
- roles: (none)
- voiceover:

narrativeRole: Opens on what the company IS, in its own three words, before anything else — answers "chi siamo" in the first beat instead of a slow visual metaphor.
keyMessage: LRC IT Solutions = Business Intelligence + Automazione + Intelligenza Artificiale.

Adapt: keep the signature move (hard-cut through value beats, resolve on the brand name) but staged across the Coral preset's own Region-Split Cover layout (blue band + cream field) instead of a flat single-color field.

Scene 1 (0.0–1.8s): Region-Split ground is present from t=0 — 38% blue top band (45° hatch, `section-label` eyebrow "LRC IT SOLUTIONS" ink, tiny, top-left) over a 62% cream field. In the blue band, three `section-headline`-scale words hard-cut flash in sequence, ink text, ~0.55s each, no fade/slide: "BUSINESS INTELLIGENCE." → "AUTOMAZIONE." → "INTELLIGENZA ARTIFICIALE." — the swap itself is the beat (kinetic-type-beats signature).
Scene 2 (1.8–3.0s): the cream field resolves — a `hero-title` "LRC IT SOLUTIONS" flash-cuts in dead-center, ink, uppercase, tracked (no per-word buildup — a single hard arrival, per the namedrop pattern's "resolve on the brand name"), with a thin blue `accent-line` drawing in beneath it left→right. Holds to the frame's exit (harness `transition_in` on Frame 2).

## Frame 2 — Cosa facciamo

- scene: Feature Stat — full blue environment, the site's own mission line reveals phrase by phrase over a wallpaper numeral "01"
- duration: 3.5s
- transition_in: squeeze
- status: animated
- src: compositions/frames/02-cosa-facciamo.html
- type: product_intro
- persuasion: Value stacking
- beat: clarity
- blueprint: compose
- focal: (typography only — no image asset)
- roles: (none)
- voiceover:

narrativeRole: Answers "cosa facciamo" with the site's own words, not an invented tagline — the value claim lands here, by beat two, per the reverse-iceberg rule.
keyMessage: "Trasformiamo dati di fabbrica e processi ripetitivi in decisioni concrete" (the site's own mission line, verbatim).

Compose (frame.md's own Feature Stat treatment already defines the shot; no roles-based blueprint needed): full-bleed blue ground with the 45° hatch and a faint `background-numeral` "01" (12% ink) seated behind the headline as wallpaper.

Scene 1 (0.0–0.5s): blue ground + hatch + wallpaper numeral "01" present from t=0, still, nothing else on screen yet (Layout: Feature Stat, centered-left focal, ~40% of the blue field left empty per frame.md's silence rule).
Scene 2 (0.5–2.6s): an ink `section-label` eyebrow "COSA FACCIAMO" cuts in top-left (0.5s), then the mission line reveals in three staggered phrase-chunks via per-word staggered reveal (`dynamic-content-sequencing`), each phrase landing on its own beat rather than one dump: "Trasformiamo dati di fabbrica" (0.7s) / "e processi ripetitivi" (1.35s) / "in decisioni concrete." (2.0s) — set at `section-headline` scale, ink, left-anchored, stacked lines.
Scene 3 (2.6–3.5s): the completed 3-line headline holds still and reads — no push, no breathe; the wallpaper numeral is the only thing with any residual life (a single low-amplitude `sine-wave-loop` jitter, finite, not a loop).

## Frame 3 — Per chi

- scene: Three-Column Catalog — the three real service verticals assemble as cards, fast stagger
- duration: 4.5s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/03-per-chi.html
- type: feature_showcase
- persuasion: Rule of three
- beat: confidence
- blueprint: grid-card-assemble (Adapt — Key_Feature: key-feature-card-grid-assemble)
- focal: (typography/geometry only — no image asset)
- roles: (none)
- voiceover:

narrativeRole: Answers "per chi lavoriamo" with the site's own three named verticals — this is the video's dense exception (Coral's Three-Column Catalog treatment), the one frame allowed to run busy.
keyMessage: One technology, three real sectors — Agenzia IA, Manifatturiero, Business & Ristorazione.

Adapt (Key_Feature grid variant): keep the signature move — labeled tiles cascade one-by-one into a 3-up grid, near-static hold with a slow push-in — cast with this brand's real three verticals instead of generic feature pills.

Scene 1 (0.0–0.6s): cream ground, `section-headline` "NON RIPARTIAMO MAI DA ZERO" (the site's own real line) cuts in centered-top, ink, uppercase. Three empty card slots are NOT pre-drawn — they arrive with their content (avoids the "empty grid" front-load).
Scene 2 (0.6–3.2s): the three `card`s (5px blue top border, 48px blue `card-icon` square, no shadow/radius) stagger-assemble left→right into the grid, ~0.5s gap between arrivals, each a short fade+slide into its slot (no scatter, no bounce): **Card 1** (0.6s) — icon: a simple ink chat-bubble glyph; `card-title` "AGENZIA IA"; body "Assistenti che rispondono, prenotano e qualificano da soli." **Card 2** (1.1s) — icon: a checkmark-in-gear glyph; `card-title` "MANIFATTURIERO"; body "Controllo qualità che non dimentica nulla." **Card 3** (1.6s) — icon: a fork-and-plate glyph; `card-title` "BUSINESS & RISTORAZIONE"; body "Il tuo locale, digitalizzato in un unico pannello." Each card's body copy staggers in via per-word reveal immediately after its card lands, finishing by 3.2s.
Scene 3 (3.2–4.5s): the completed 3-card grid holds near-static with one slow, faint camera push-in (≤3% scale over the window) — the only camera move in the whole video, per `grid-card-assemble`'s own doctrine; no other motion competes with it.

## Frame 4 — Chiudiamo

- scene: Closing Plate — the tagline assembles fast, the wordmark lands, a contact line completes the sign-off
- duration: 4s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/04-chiudiamo.html
- type: branding
- persuasion: Identity resolution — the brand's own tagline (not a stat) is the payoff
- beat: confidence
- blueprint: logo-assemble-lockup (Adapt — Brand_Outro: settled-lockup-reveal, sped up)
- focal: (typography only — no image asset)
- roles: (none)
- voiceover:

narrativeRole: The closing brand hold — still no "+24%" stat — but now lands with a fast, kinetic assemble instead of v1's long static hold, per the "more movement" note.
keyMessage: "Il tuo processo. La nostra priorità." — wordmark "LRC IT SOLUTIONS" — a real contact line, not a generic CTA button.

Adapt: keep the signature move (a lockup completes on screen) but sped up and busier than v1 — this is the fast, kinetic version the user asked for, not the slow one-beat reveal from the first cut.

Scene 1 (0.0–1.6s): cream field; "Il tuo processo." hard-cuts in centered (`section-headline`, ink) at t=0.1s; "La nostra priorità." hard-cuts in beneath it in blue at t=0.6s — two fast arrivals, not a slow per-word build (more movement, fewer, punchier beats).
Scene 2 (1.6–2.6s): a blue `accent-line` draws left→right beneath the tagline (1.6–2.0s); the bottom `info-bar` band (blue, `bar-title` left + `section-label` right) slides up into place (2.0–2.6s) carrying the wordmark "LRC IT SOLUTIONS" (left) and the real contact line "info@lrc-solutions.com" (right, from the site's own footer).
Scene 3 (2.6–4.0s): everything settles — this is the video's one legible hold (per Video Direction, ≤1.2s of real stillness), but it is not dead: a final low-amplitude jitter plus a last accent flourish (the accent-line's leading edge glows briefly) keeps it visibly alive up to the real end of the video.
