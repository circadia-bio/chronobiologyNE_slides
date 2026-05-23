# 🕰️ chronobiologyNE_slides

> Presentation slides for the **Chronobiology Northeast Meeting 2026**  
> *"Building Open Research Infrastructure for Chronobiology"*  
> Lucas França & Mario Leocadio-Miguel · Circadia Lab

---

## 📖 Contents

An overview of the open-source tools developed at the Circadia Lab:

| Tool | Type | What it does |
|------|------|--------------|
| 🌙 **Sleep Diaries** | Mobile/web app | Participant sleep diary + validated questionnaires |
| 📋 **ScoreMe** | Mobile/web app | Lab-based questionnaire administration for cohorts |
| 🛏 **slumbR** | R package | Import & analyse Sleep Diaries exports |
| 🧮 **tallieR** | R package | Import & analyse ScoreMe exports |
| 🐳 **circadiaBase_Docker** | Docker environment | Reproducible Python + R research environment |

---

## 🚀 Rendering the slides

### Prerequisites

- [Quarto](https://quarto.org) ≥ 1.4
- A browser (slides run as HTML/RevealJS — no LaTeX needed)

### Render

```bash
quarto render index.qmd
```

Or start a live-preview server:

```bash
quarto preview index.qmd
```

### Output

The rendered presentation is written to `docs/`. Open `docs/index.html` in any browser.

---

## 🗂️ Structure

```
chronobiologyNE_slides/
├── index.qmd          # Main presentation source
├── custom.scss        # Circadia Lab RevealJS theme
├── _quarto.yml        # Project config
├── assets/
│   └── logo.png       # Circadia Lab logo (add manually)
└── docs/              # Rendered output (git-ignored or served via Pages)
```

---

## 🔗 Links

| | |
|--|--|
| Lab | [circadia-lab.uk](https://circadia-lab.uk) |
| Sleep Diaries | [sleepdiaries.circadia-lab.uk](https://sleepdiaries.circadia-lab.uk) |
| ScoreMe | [scoreme.circadia-lab.uk](https://scoreme.circadia-lab.uk) |
| GitHub org | [github.com/circadia-bio](https://github.com/circadia-bio) |

---

## 👥 Authors

| Role | Name |
|------|------|
| Presenter / Developer | Lucas França |
| Presenter / PI | Mario Leocadio-Miguel |

Copyright © Circadia Lab — Lucas França & Mario Leocadio-Miguel
