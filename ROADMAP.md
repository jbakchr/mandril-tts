# 🗺️ mandril-tts — Roadmap

This roadmap is a _direction_, not a plan.

It exists to:

- help future me remember what this project could become
- reduce friction when picking it up again
- keep things moving in small, fun steps

---

## 🧭 Guiding principle

> Start simple → make it work → make it weird → make it fun

---

## ✅ Phase 0 — Exploration (low friction start)

Goal: get _something_ working quickly

- [ ] Install and run Chatterbox-TTS locally
- [ ] Generate basic Danish speech from text
- [ ] Save / play audio output
- [ ] Test different types of text:
  - normal sentences
  - weird / absurd sentences
  - uppercase / punctuation-heavy input

**Outcome**

- “It works”
- First sense of how Danish sounds

---

## 🔧 Phase 1 — Minimal tooling

Goal: make it easy to use repeatedly

### CLI prototype

- [ ] Create a simple script:
  ```bash
  $ mandril "some text"
  ```

* [ ] Auto-play audio output
* [ ] Keep output formatting clean (input → output)

### Small improvements

- [ ] Add random example mode
- [ ] Add quick “test phrases”

**Outcome**

- One-command fun
- Feels like a toy you can actually use

---

## 🎭 Phase 2 — Voice & style experimentation

Goal: move beyond “just TTS”

### Style exploration

- [ ] Test different text patterns:
  - pauses (`...`)
  - emphasis (CAPS)
  - repetition
- [ ] Try different tones:
  - dramatic
  - calm
  - chaotic

### Voice cloning (optional)

- [ ] Test with reference audio
- [ ] Explore “character-inspired” voices

### Early “modes”

- [ ] Introduce flags:
  ```bash
  $ mandril --mode dramatic "text"
  $ mandril --mode chaos "text"
  ```

**Outcome**

- Starts to feel like _something unique_, not just TTS

---

## 😄 Phase 3 — Fun features (lean into the weird)

Goal: make it delightful

### Interaction ideas

- [ ] “Surprise me” mode
- [ ] Random voice/style generator
- [ ] Random absurd text generator (LLM or predefined)

### Chaos mechanics

- [ ] “Chaos level” (0–10)
- [ ] Increasing intensity over time
- [ ] Unexpected pauses / rhythm

### Personality experiments

- [ ] Passive-aggressive voice
- [ ] Overly dramatic narrator
- [ ] Completely calm but absurd

**Outcome**

- You don’t just use it — you _play with it_

---

## 🌐 Phase 4 — Interfaces (optional)

Goal: make it easier to interact with

### Web UI

- [ ] Simple page:
  - input field
  - play button
- [ ] Style toggles (drama / chaos / etc.)

### Chrome extension

- [ ] Highlight text → “Play as Mandril”
- [ ] Integrate into your existing extension patterns

### API (FastAPI)

- [ ] `/tts` endpoint
- [ ] Easy integration with other projects

**Outcome**

- Becomes reusable across your tools

---

## 🔗 Phase 5 — Integrations (optional / interesting)

Goal: connect to other ideas

- [ ] Use with `microsteps-ai`:
  - spoken steps in Danish
- [ ] Use with summarizers:
  - “listen instead of read”
- [ ] Combine with LLM:
  - generate absurd monologues automatically

**Outcome**

- Starts to blend into your broader tool ecosystem

---

## 🧪 Phase X — Unexpected directions

This project is allowed to go off-track.

Possible directions:

- absurd storytelling generator
- voice-based mini “sketches”
- interactive voice loops
- emotional/intensity experiments

If something feels interesting:
→ follow that instead of the roadmap

---

## 🛑 Anti-goals

Things this project is NOT trying to be:

- perfect voice cloning
- polished production system
- scalable SaaS product
- overly structured or complex

---

## ✅ Definition of success

- You open the tool
- You type something stupid
- You laugh (or at least smile)

---

## 📝 Notes to future me

- Keep it small
- Avoid over-engineering
- If it feels like work → simplify
- If it feels fun → continue
