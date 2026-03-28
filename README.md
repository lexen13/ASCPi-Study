# ASCPi-Study
ASCPi Study guide for my mahal when shes on the go. 
# ASCP BOC MLS(ASCPi) Study App

## Clinical Scenario Flashcard App for the ASCP Board Exam

A mobile-friendly study app with 57 scenario-based and recall cards covering all 7 ASCP BOC content areas. Built for Filipino MedTech graduates challenging the MLS(ASCPi) certification.

---

### Study Modes

| Mode | How It Works |
|---|---|
| 🎯 **Multiple Choice** | Pick A/B/C/D, get instant feedback + full explanation. Closest to real CAT exam format. |
| ✍️ **Free Response** | Type your answer in your own words. App checks against key clinical concepts (keyword matching, not exact string). Shows which concepts you identified correctly. |
| 🔄 **Flip Cards** | Read the scenario, tap to reveal the answer + explanation. Quick review mode. |

### Content Distribution

| Area | Cards | Exam Weight |
|---|---|---|
| Blood Banking | 10 | 17-22% |
| Chemistry | 10 | 17-22% |
| Hematology | 10 | 17-22% |
| Microbiology | 10 | 17-22% |
| UA & Body Fluids | 7 | 5-10% |
| Immunology | 5 | 5-10% |
| Lab Operations | 5 | 5-10% |

### Features

- **Category filtering** — Focus on weak areas
- **Streak counter** 🔥 — Tracks consecutive correct answers
- **Running score** — Correct / Wrong / Total with percentage
- **Shuffle on restart** — Different card order every session
- **Session results** — Score summary at the end
- **Mobile-first design** — Built for phone screens
- **Zero dependencies** — Single HTML file, no build tools, no npm
- **Works offline** — Once loaded, no internet needed

### Files

```
index.html                        ← Study app (open in browser or deploy to GitHub Pages)
ASCP-BOC-MLS-Study-Guide.md      ← Full written study guide with 100-question practice exam
README.md                         ← This file
```

### How Free Response Checking Works

Each card has clinical keywords. If your typed answer contains **2 or more key concepts**, it's marked correct:

- **Q:** "What causes a falsely decreased HbA1c?"
- ✅ "hemolytic anemia because the rbc lifespan is shortened" → matches `hemolytic` + `rbc lifespan` + `shortened`
- ❌ "diabetes" → no keyword matches

This forces you to explain the *why*, not just memorize answer letters.

---

*Content aligned with ASCP BOC MLS/MLSi Content Guideline (Revised July 2023).*
