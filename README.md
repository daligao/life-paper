# 900 Squares — The Human Life Archive

**[🔴 Live Demo → ordinarymantrying.com/tools/life-paper/](https://ordinarymantrying.com/tools/life-paper/)**  
**[▶ Open on GitHub Pages →](https://daligao.github.io/life-paper/)**

![900 Squares — Human Life Archive](screenshot.png)

> 75 years. 900 squares. Each one is a month.  
> These people had almost nothing on their paper for decades. Then one square changed everything.

---

## What It Does

A single-file HTML tool that lets you explore famous lives — and your own place in time — on a 900-square grid. No personal data required. No sign-up.

**7 lenses to explore:**

| Lens | Description |
|---|---|
| 📖 Famous Lives | Watch Chu Shijian, Grandma Moses, Colonel Sanders animate. Enter your age to see where you stand on their paper. |
| 🎲 Random Life | A stranger's paper, randomly assembled. You'll recognize yourself in it. |
| 🌍 Generation | The average paper for Post-80s, Post-90s, Post-00s. Are you ahead or behind? |
| 🎭 Role Swap | 8 roles — migrant, caregiver, artist, ICU nurse. Same grid, different story. |
| ⚖️ Life Exchange | Pick life "packages." The grid shows what you're actually building. |
| 🕯️ Collective Memorial | What millions said about each square, sorted by age. |
| 🎰 Fate Machine | You didn't choose where you started. Neither did most people. |

**Bonus features:**
- 💛 **Golden Zone** — calculate how many months you have left with your parents
- 🛡️ **Regret Shield** — 3 risk checks before it's too late
- 📚 Book recommendations (Amazon affiliate links)
- ☕ Ko-fi support button

---

## Why It Exists

Built as part of [Ordinary Man Trying](https://ordinarymantrying.com/) — a public experiment in building a blog + tool suite using AI, with zero tech background.

[Read the story →](https://ordinarymantrying.com/building-in-public-experiment/)

---

## Technical

- Single HTML file (no dependencies, no build step)
- Light/elegant theme with GPU-composited cell animations
- 900-cell DOM pool — created once, reused on every render
- Event delegation for tooltip handling
- `localStorage` for onboarding + Regret Shield state
- `@media print` support

---

*Part of the [Free Tools](https://ordinarymantrying.com/tools/) collection.*
