---
format: 1920x1080
duration: 15s
message: "LRC turns messy manual process and factory data into one clear, automated decision"
arc: BAB (compressed) — before (raw texture) → resolve/bridge (product surfaces) → brand (tagline lockup)
audience: manufacturing, restaurant, and service-business operators (Italian-speaking)
mode: autonomous
music: none
---

## Video direction

- **Palette system** (from `frame.md`, never invented): white/cream canvas, near-black `text` for every headline, a single saturated cobalt `#2563EB` (`primary`) as the ONLY accent — underlines, glows, the tinted-card fill, the wordmark pop. No second accent color anywhere.
- **Motion grammar + reveal model**: long-tail `power3` decel on every entrance (no bounce/overshoot). This piece is **silent** (no VO), so reveals are paced to **on-screen text cues** instead of spoken ones — the same anti-PowerPoint law applies: nothing dumps at t=0, each line/photo/wordmark lands on its own beat, spread across the back half of its frame. During any hold, at most a subtle jitter (`sine-wave-loop`, low amplitude) keeps it alive — no lazy breathing, no back-half pan/push.
- **Rhythm / held-frame allocation**: Frames 1–2 are the active reveal (texture → resolve); Frame 3 is the deliberate held/breather frame — per `logo-assemble-lockup`'s own doctrine, its final beat holds dead-static once the lockup completes.
- **Negative list**: no stock "AI" bokeh/gradients, no invented stats or percentages (the declined "+24%" stays out entirely — frame.md's hard numerals rule applies with extra force here), no bouncy/elastic easing, no infinite/looping motion, no camera pan or push in any back half, no captions track (silent piece, nothing to caption).

## Frame 1 — Il rumore

- scene: Real industrial-automation photo, texture-close, with the site's own problem language fragmenting across it
- duration: 5s
- transition_in: cut
- status: animated
- src: compositions/frames/01-il-rumore.html
- type: hook
- persuasion: Pain validation
- beat: overwhelm
- asset_candidates: assets/automazione-in-ambiente-industriale-mode.jpg — real photo, automation in an industrial environment
- voiceover:
- blueprint: kinetic-type-beats (Adapt — Problem: problem-kinetic-type-beats)
- focal: assets/automazione-in-ambiente-industriale-mode.jpg
- roles: automazione-in-ambiente-industriale-mode.jpg = background (full-bleed, dimmed ~35% under a cobalt-tinted overlay)

narrativeRole: Opens on unresolved texture, not a company description — a purely visual hook (no VO) that reads as tension before any claim is made.
keyMessage: Manual process and disconnected factory data are the starting condition.

Adapt: keep the signature move — a short pain line lands alone, no product visible yet, then the next line replaces it — but the canvas is the real photo instead of a flat color field.

Scene 1 (0.0–2.2s): the industrial-automation photo is present from t=0, full-bleed, static, dimmed ~35% under a cobalt-tinted overlay for legibility (Layout: full-width strip, background layer). "Dati fermi." lands centered in the lower-middle third — clear of the bottom caption-band keep-out — via a per-word staggered reveal on a smooth `power3` settle; a thin cobalt underline draws left→right beneath "fermi."
Scene 2 (2.2–5.0s): "Dati fermi." clears (quick fade) as "Processi manuali." hard-cut flash-replaces it in the same position — the swap itself is the beat. The photo stays completely static underneath (no pan/push); holds to the frame's exit (the harness `transition_in` on Frame 2).

## Frame 2 — La lettura

- scene: The industrial texture resolves into the real BI dashboard photo; the site's own solution line lands as it settles
- duration: 5s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/02-la-lettura.html
- type: product_intro
- persuasion: Negative contrast
- beat: relief + control
- asset_candidates: assets/dashboard-di-business-intelligence-con-g.jpg — real photo, business intelligence dashboard
- voiceover:
- blueprint: compose
- focal: assets/dashboard-di-business-intelligence-con-g.jpg
- roles: automazione-in-ambiente-industriale-mode.jpg = supporting (outgoing, first ~1s only, same framing as Frame 1's hold); dashboard-di-business-intelligence-con-g.jpg = cutout (incoming, resolves to full-bleed focal)

narrativeRole: The value claim lands here, by beat two, per the reverse-iceberg rule — the same visual world resolves from raw texture into a legible product surface.
keyMessage: "Trasforma i dati in decisioni" — data becomes a decision, not a stat.

Compose (no blueprint fits a two-still silent morph cleanly): still pace the reveal across the shot, never front-load.

Scene 1 (0.0–1.0s): continues Frame 1's held photo one beat longer — full-bleed, static, still dimmed, no text — before anything moves.
Scene 2 (1.0–3.2s): a `card-morph-anchor` handoff — the photo's apparent surface morphs (a scale + corner-radius shift toward frame.md's 14px card radius) directly into the dashboard photo revealed beneath it; a soft cobalt `ambient-glow-bloom` marks the seam. One continuous transformation, never a hard cut.
Scene 3 (3.2–5.0s): the dashboard photo settles full-bleed as the focal image (~55% density, Layout: full-width strip). "Trasforma i dati in decisioni" — the site's own solution line — reveals via a per-word staggered fade inside a card-tinted band in the lower-middle third — clear of the bottom caption-band keep-out (frame.md's `card-tinted`, 4% cobalt fill). Holds still once landed; at most subtle jitter, no back-half push.

## Frame 3 — La priorità

- scene: The dashboard photo dissolves into the brand tagline card, closing on the wordmark
- duration: 5s
- transition_in: crossfade
- status: animated
- src: compositions/frames/03-la-priorita.html
- type: branding
- persuasion: Identity resolution — the brand's own headline claim (not a stat) is the payoff the whole video resolves to
- beat: confidence
- voiceover:
- blueprint: logo-assemble-lockup (Adapt — Brand_Outro: brand-outro-assemble-logo-lockup)
- focal: (typography only — no image asset; pure lockup beat)
- roles: (none — dashboard photo from Frame 2 clears at Scene 1, no asset carried into this frame)

narrativeRole: The closing brand hold — deliberately swaps the "+24%" stat the user declined for the site's own headline claim as the resolve target.
keyMessage: "Il tuo processo. La nostra priorità." over the wordmark "LRC Solutions" — no stat, no CTA; a calm, confident close for a muted website-embed placement.

Adapt: keep the signature move (the stage clears, then the lockup builds into being) but there is no icon/mark asset to stroke-draw — only a wordmark — so the tagline text itself is the material that assembles, and the wordmark completes the lockup beneath it.

Scene 1 (0.0–1.2s): Frame 2's dashboard photo clears the stage — shrinks + fades toward center (the exit half of a `scale-swap-transition`) onto frame.md's empty cream canvas, per the Brand_Outro "stage clears" beat.
Scene 2 (1.2–3.2s): on the cleared canvas, "Il tuo processo." lands first (near-black `h1`, centered, `Closing/CTA` treatment) via a per-word staggered reveal; "La nostra priorità." reveals beneath it a beat later in cobalt (`blockquote`/`h2` ramp) — the tagline is the raw material the lockup assembles from.
Scene 3 (3.2–5.0s): the wordmark "LRC Solutions" settles beneath the tagline via a whole-word spring-pop entrance (`spring-pop-entrance`, smooth `power3`, no overshoot), completing the lockup. Holds dead-static for this final beat — the video's one deliberate long hold; at most subtle jitter (`sine-wave-loop`, low amplitude).
