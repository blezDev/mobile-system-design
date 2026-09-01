# Mobile Systems Blueprint

An interactive, single-file HTML site for learning mobile system design — caching, offline sync, image loading pipelines, resumable downloads, chat systems, Stories-style features, and real-world architecture case studies (Facebook, WhatsApp) — with a flashcard quiz mode.

Content is distilled from [awesome-mobile-system-design](https://github.com/yogeshpaliyal/awesome-mobile-system-design).

> **⚠️ For learning purposes only.** This project is an unofficial, self-made study aid. It is not affiliated with, endorsed by, or sourced verbatim from any company, book, or the linked repository's maintainer. Diagrams and explanations are original summaries of publicly known mobile engineering concepts, written to help with interview prep and self-study — not a substitute for the primary sources it links to.

## How to use it

No build step, no server, no GitHub Pages needed — it's one self-contained `index.html` file.

- **Easiest:** grab `index.html` from the [latest release](../../releases/latest) and double-click it — it opens straight in your default browser.
- **Or:** clone this repo and open [`index.html`](index.html) directly.

Your progress (sheets visited, flashcards mastered) is saved locally in your browser via `localStorage` — it stays on your machine and isn't sent anywhere.

## What's inside

- **A0** — the interview framework (requirements → high-level design → deep dive → wrap-up)
- **A1–A4** — building blocks: caching, sync & offline networking, image loading pipelines, resumable file downloads
- **A5–A6** — feature case studies: chat systems, Instagram-style Stories
- **A7** — real-world architecture: Facebook vs. WhatsApp
- **Quiz mode** — 24 flip-to-reveal flashcards with mastery tracking
