# Exponent Stacking Playground — README

> *“Insight is superior to analysis.”*
> **Mission:** Give people a gut‑level feel for how lifestyle & mindset choices can **multiply** the raw pace of technological growth.

---

## 🚀 Quick Start

1. **Clone / download** the repo *(or just grab the single `index.html` you see next door).*
2. **Open** `index.html` in any modern browser (desktop or mobile).
3. **Drag the sliders** → watch the blue line go **whoosh**.

That’s it. No build steps, no servers, no package managers. **Pure CDN‑powered HTML + Chart.js**.

---

## 🎛️  What the Sliders Mean

| Slider                    | What it measures                                  | How it’s turned into a multiplier |
| ------------------------- | ------------------------------------------------- | --------------------------------- |
| **Words Per Minute**      | Your spoken input speed when dictating to an LLM. | `wpm / 150` (baseline 150 wpm)    |
| **AI Interactions / day** | How many distinct chats you have.                 | `1 + (value − 5)/5`               |
| **Prompt Skill**          | Your grasp of context windows, system roles, etc. | Same linear → multiplier formula  |
| **Personal Insight**      | Self‑awareness & meta‑cognition.                  | idem                              |
| **Context Revealed**      | How much relevant background you feed the model.  | idem                              |
| **Relation to AI**        | From adversarial (0) to fully collaborative (10). | idem                              |

The **six multipliers are multiplied together** → `stackMultiplier`.

---

## 🔬 The Math Under the Hood

```text
baseGrowth       = 1.40          # ≈ 40 % compound annual tech curve
stackMultiplier  = wpmMult × freqMult × skillMult × insightMult × contextMult × relationMult

effectiveGrowth  = baseGrowth × stackMultiplier
impact(year)     = effectiveGrowth^year
```

*Linear Y‑axis.* Why? Putting this on a log scale would hide the fireworks — we **want you to feel** those jumps between `10¹`, `10²`, `10³`…

If the curve still looks tame, crank `baseGrowth`, add more sliders, or nest another exponent. 🧨

---

## 🛠️  Tweaking / Extending

* **Change the baseline**: edit `baseGrowth` in `index.html`.
* **Add sliders**: duplicate a `.slider-group`, give it a new `id`, and fold it into `stackMultiplier`.
* **Style**: everything is vanilla CSS — go nuts with Tailwind, dark mode, or neon cyber‑punk.
* **Share**: throw the file on any static host or send it to friends. It’s under **MIT License** — no permission slips needed.

---

## 🧑‍🤝‍🧑  Philosophy Note

Stacking exponents isn’t about raw speed alone. The dramatic spikes come from **human factors** — insight, skill, partnership. Tech improves anyway; **we** decide whether it’s a gentle slope or a catapult.

---

## 📜  License

MIT — do anything, just keep the notice.

---

## ✉️  Contact & Credits

Built by **Kai**. Questions, forks, memes → open an issue or ping `@your‑handle`.

---

