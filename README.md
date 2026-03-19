# 🐒 The Monkey Care Guide

**A neurodivergent-informed interactive decision tree for partners who want to help but aren't quite sure how.**

Live demo: [your-url-here.vercel.app](https://your-url-here.vercel.app)

---

## What is this?

This is a single-page interactive guide designed to help a partner support someone who has **ADHD and is in perimenopause** when they're having a difficult moment and may not have the self-awareness or vocabulary to explain why. It's written by me, Monkey, for my autistic husband. I know he wants to help, but this mix of ambiguity and emotions are his kyrptonite.

It works as a click-through diagnostic tree. The supporter answers a short series of questions about what they're observing, and the guide produces a probable diagnosis and a set of concrete, specific interventions with explanations of *why* each one works at a neurological level, not just "be supportive." Fewer feelings, more facts!

It was built with a specific couple in mind (one partner with ADHD + perimenopause, one autistic partner), but the underlying logic is grounded in publicly available research on ADHD and perimenopause, and may be useful more broadly. Maybe you're the monkey, maybe you're the mechanic.

---

## Why does this exist?

Supporting someone with ADHD through a low moment is hard when:

- Their self-awareness isn't always great in the moment
- You don't know if it's physiological (they're tired, hungry, hormonal), or something else
- Your instincts (teasing, logic, problem-solving) consistently backfire
- You get stressed not knowing what to do, so you hide in the basement playing Vermintide 2 which makes things worse

This guide turns an ambiguous emotional situation into a structured diagnostic process. 
One both more accessible for neurodivergent supporters and more useful than generic advice like "just be there for her."

---

## What's in the tree?

The guide checks in this order, then routes to a result with a suggested phrase to validate the diagnosis. Each result includes a reassess CTA that routes to the next most logical point in the tree if the diagnosis doesn't fit. After three failed reassessments the tool stops trying to diagnose and routes to a final state: bring her a glass of water and leave her alone for an hour. Too many questions are part of the problem.

### Diagnostic flow

The guide checks in this order:

1. **Hunger** — ADHD brains burn through glucose fast. Low blood sugar is chemically indistinguishable from emotional dysregulation. Always checked first.
2. **Sleep** — Poor sleep mimics almost every emotional state. Perimenopause disrupts sleep significantly.
3. **Cause** — Did something trigger this, or did it arrive without warning? (Hormonal episodes often have no external cause.)
4. **Mood type** — Withdrawn, irritable/restless, or feeling rejected/unseen.
5. **Specifics** — Within each mood type, follow-up questions narrow the likely cause.

### Assessment

| Assessment | What it means |
|---|---|
| 🍌 Hungry Monkey | Low blood sugar presenting as emotional dysregulation |
| 😴 Sleep-Depleted Monkey | Sleep debt removing emotional shock absorbers |
| 🌫️ Hormonal Weather Monkey | Perimenopause oestrogen drop — no external cause, will pass |
| 🌊 Overwhelmed Monkey | ADHD stress bucket full — capacity depleted |
| 💔 Feeling Rejected or Unseen (RSD) | Rejection Sensitive Dysphoria active |
| 🔁 Routine-Bored Monkey | Too much predictability starving dopamine |
| 🌀 Unanchored Monkey | Too much chaos, no routine anchor |
| ✨ Whimsy-Depleted Monkey | Novelty and play deficit — dopamine low |

### Treatments

Each diagnosis maps to ordered treatment recommendations, each with a **"Why this works"** note explaining the neurological mechanism:

| Treatment | What it means |
|---|---|
|🍌 Feed | glucose restoration |
🌿 Quiet Together Time — presence without pressure
🌳 Take Outside — movement as direct dopamine medicine
🎨 Creative / Craft Time — dopamine via making
🎪 Add Whimsy — novelty and surprise as dopamine medicine; prepare in advance
⭐ Focused, Specific Attention — RSD intervention; specificity matters more than volume
🌙 Rest Protocol — sleep debt management
🌸 Hormonal Weather Protocol — warmth without understanding or fixing
💧 Give Her Space — the only treatment that asks you to leave; bring water, set a timer, ask once after an hour

---

## The research behind it

This guide draws on publicly available research on:

- **ADHD and perimenopause interaction** — oestrogen's role in dopamine regulation; why perimenopausal women with ADHD often experience amplified symptoms
- **Rejection Sensitive Dysphoria (RSD)** — a neurological feature of ADHD affecting ~70% of adults; why perceived rejection causes disproportionate pain and what actually helps
- **Dopamine and ADHD** — why novelty, movement, and creative activity are physiological needs, not preferences
- **Sleep and ADHD** — the particular vulnerability of ADHD brains to sleep deprivation's emotional effects

Key sources include ADDitude Magazine, CHADD, the Attention Deficit Disorder Association (ADDA), Cleveland Clinic, and peer-reviewed literature on ADHD in women.

---

## Technical details

This is a single `index.html` file with no dependencies, no frameworks, no build step, and no data collection. It runs entirely in the browser.

- **Fonts:** Google Fonts (Fredoka One, Nunito) — loaded from CDN
- **JavaScript:** Vanilla JS, ~100 lines
- **Storage:** None. Nothing is tracked or stored.
- **Hosting:** Works with any static host — Vercel, Netlify, GitHub Pages, etc.

---

## Using or adapting this

This is open source. If it's useful to you as-is, use it. If you want to adapt it for your own relationship dynamic, the decision tree logic lives in two JavaScript objects at the bottom of `index.html`:

- `nodes` — the questions and branching logic
- `treatments` — the intervention cards and their content

Both are plain objects and straightforward to edit without any coding background.

If you make a version for a different neurodivergent combination (e.g. both autistic, or ADHD + depression, or any other pairing), please consider sharing it.
If you make a version that improves on this (form, function, or fun), please consider submitting an update.

---

## A note on tone

This guide is deliberately light-hearted in framing. The person it was made for is referred to as "Monkey". that's me and this is a term of endearment, not a label. The whimsy is intentional; when someone is stressed and doesn't know what to do, a guide that is warm and slightly silly is more likely to actually get used than a clinical one. The tone and the language aren't chosen to make fun of or light of what can be difficult, confusing, painful, stressful and upsetting. The tone and and the language are used to avoid pathologising one of life's most common experiences. The Monkeys aren't sick. This is normal.

The content, however, is grounded in real research. The "Why this works" sections exist specifically because one partner in this dynamic is autistic and processes things better when the logic is made explicit rather than implied.

---

## Disclaimer

This is a personal tool shared publicly in case it's useful to others. It is not medical advice. It does not replace professional support for ADHD, perimenopause, or relationship difficulties. If you're struggling, please also talk to a doctor or therapist who understands neurodivergence.

---

*Made with love. Open source. 🌿*
