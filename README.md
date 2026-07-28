# Closeout & Improvement Manager — Digital Worker

An interactive briefing deck explaining the IFS.ai **Closeout & Improvement Manager (CIM)** digital worker: what a digital worker is, the four skills CIM runs, the order it runs them in, and the guardrails that keep a person in control.

Built for explaining the concept in a room. Seven slides, three of them interactive.

## Viewing it

Open `index.html` in any modern browser — or use the GitHub Pages URL if Pages is enabled for this repo.

The file is **completely self-contained**: fonts, D3 and the IFS mark are all embedded. No CDN, no build step, no network connection required. Copy it to a USB stick and it still works.

## The interactive bits

| Slide | What to do |
| --- | --- |
| The digital worker and its skills | Hover the centre or any of the four skills — the panel on the right explains each one |
| The order it works in | Hover any gate, and the drop-out box underneath |
| What comes out of one job | Hover the input note or any of the four outcomes |

## Presenting it

| Key | Action |
| --- | --- |
| `→` `←` `Space` | Next / previous slide |
| `Home` `End` | First / last slide |
| `N` | Speaker notes panel |
| `Shift` + `N` | Detach notes into a second window (position, notes, next slide, timer) |
| `O` | Overview grid — click to jump, drag to reorder, hover + `H` to hide |
| `H` / `Shift` + `H` / `U` | Hide current slide / hidden-slides picker / restore all |
| `F` | Fullscreen |
| `?` | All shortcuts |

Slide order and hidden slides persist in `localStorage`, so a deck trimmed for one audience stays trimmed until you press `U`.

> Detached presenter notes (`Shift` + `N`) opens a popup. That works when running the file locally; some hosted contexts block popups.

## Design

Nexus Black / IFS Resolve: dark ground, violet accent used once per slide, Inter Tight with JetBrains Mono for anything that is data. The stage is a fixed 1280×720 canvas that scales to whatever window it lands in.

## Source

Content is drawn from the CIM digital worker specification — the orchestration logic and the four skill definitions. Slide copy deliberately stays at concept level: no document numbers, no customer data, no metrics.
