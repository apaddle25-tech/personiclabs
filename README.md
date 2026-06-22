# Personic Labs — Premiumized Brand & Product System

A unified, premium redesign across the full Personic Labs experience. One dark
"Spectral" design system now runs across the website and the assessment, with a
dedicated **light** theme for the results report (for long-form readability).

## Design system — "Spectral"
- Dark, atmospheric base with a fine grain and a spectral aurora drawn from the
  faceted "play-P" logo mark.
- Five Acoustic Genome channels inside SoundTrack as the color language:
  Exploration (violet), Structure (blue), Activation (teal), Connection (rose),
  Sensitivity (amber) — used as wayfinding, sparingly.
- Type: **Axiforma** (display/body) + a monospace utility face for lab-instrument
  labels. Editorial spacing, numbered process, contained CTA panels.
- Signature motifs: live spectral equalizer, SoundTrack pentagon/radar,
  OCEAN color dots, closing waveform.
- Shared stylesheet: `assets/personic.css` (tokens + components for every page).

## Website (multi-page, dark)
Open `index-standalone.html` (or `index.html`). All pages share `assets/personic.css`.
- `index-standalone.html` / `index.html` — flagship home (waitlist CTA)
- `index-live-product-standalone.html` — home variant (CTA → live assessment)
- `personic-soundtrack-standalone.html` — the core consumer product, SoundTrack: OCEAN radar, the five
  SoundTrack Types, the 5-step experience, example report, color evolution, domains
- `wavelength-how-it-works.html` — the science page: signal design + 8 musical building
  blocks + genome→archetype (legacy filename retained for routing)
- `wavelength-standalone.html` — Wavelength, with the MBTI / DISC comparison table
- `waitlist-standalone.html` — waitlist with full intake form
- `about-us-standalone.html` — founder story, research foundation, and Personic Labs mission

## Assessment (interactive, dark)
- `personic-soundtrack-assessment.html` — the 15-step SoundTrack sound-first flow, refined onto the
  Spectral system (mono eyebrows, pill buttons, refined fields, spectral flow bar,
  spectral pentagon on the processing step). Uses `assets/`.
- `personic-acoustic-genome-assessment-export.html` — the same SoundTrack flow, **self-contained**
  (all fonts/logos inlined; opens anywhere with no network).

## Results report (light)
- `personic-results-report-export.html` — the full results report in a premium
  **light** theme for readability, **self-contained**. The genome identity hero is
  kept as one dramatic dark focal panel so the signature visual stays intact.
  Premium-gated sections and the crisis-support footer are preserved.

## Assets
`assets/personic.css`, `assets/fonts/` (Axiforma woff2, Gilroy/AvantGarde ttf),
`assets/logos/` (play-P mark + favicon), `assets/img/` (hero portrait, press + research logos).

© 2026 Personic Labs, Inc.
