# 🧬 MetaliBot Knowledge Base

> **AI Health Education Guide** | Metabolic Science · Clinical Observation · Natural Health
> Bilingual (English / Spanish) · Education-First · Empowerment-Driven

---

## What Is MetaliBot?

MetaliBot is an AI health education assistant grounded in metabolic science and clinical observation. It helps people understand how their metabolism works, why conventional dieting fails, and what the body truly needs to heal, lose fat, regain energy, and manage chronic conditions — naturally.

**Core truth:** *"Diets don't work if you don't fix your metabolism first."*
**Core belief:** *"The body is perfect. When given the right conditions, it always heals."*
**Core promise:** *"La verdad siempre triunfa."*

---

## 📁 Repository Structure

```
MetaliBot-Knowledge-Base/
├── README.md
├── system-prompt/
│   └── metalibot_system_prompt_v5.md       ← Paste this into Claude Project
├── knowledge-base/
│   ├── 01_plate_proportion_3x1.md          ← Full food lists, Type A/E, cultural examples
│   ├── 02_food_aggressors_TAM.md           ← TAM framework, glucometer test, elimination method
│   ├── 03_candida_albicans.md              ← 22 symptoms, 78 toxins, protocol, warts connection
│   ├── 04_insulin_resistance.md            ← Cell receptor mechanism, reversal protocol
│   ├── 05_magnesium_potassium.md           ← Dosing, citrate form, 68% deficiency, conditions
│   ├── 06_green_vegetable_juices.md        ← Exosome science, recipes, juicer vs blender
│   ├── 07_fatty_liver.md                   ← T4→T3 link, liver cleanse, thyroid restoration
│   ├── 08_nervous_system_types.md          ← Excitado/Pasivo fuel types, food-emotion link
│   ├── 09_medications_metabolism.md        ← Antidepressants, statins, hormonal contraceptives
│   ├── 10_extreme_diets_hcg.md             ← Muscle destruction mechanism, glucagon, yo-yo
│   ├── 11_hydration.md                     ← Formula, what counts, urine guide, dehydration-hunger
│   ├── 12_coconut_oil_mct.md               ← MCT science, lauric acid, antifungal properties
│   ├── 13_core_beliefs.md                  ← 3 foundational principles, empowerment framework
│   ├── 14_diabetes_clinical_guide.md       ← ⭐ Full diabetes protocol from Problem-Free Diabetes
│   ├── 15_clinical_glossary.md             ← ⭐ 50+ precise clinical definitions (A1c to Vasopressin)
│   ├── 16_el_poder_del_metabolismo_core.md ← ⭐ Core teachings: enemies, Mediterranean insight, addiction
│   ├── 17_sugar_fructose_enemy.md          ← ⭐ HFCS, glucose-insulin loop, carb addiction science
│   ├── 18_hypothyroidism_temperature_test.md ← ⭐ Temperature test, T4→T3, goitrogens, subclinical
│   ├── 19_stress_cortisol_weight.md        ← ⭐ Cortisol mechanism, belly fat, adaptogens
│   └── 20_research_bibliography.md         ← ⭐ Full bibliography from medical literature
└── videos/
    └── video_reference_library.md          ← 10 videos with routing logic + view analysis
```

⭐ = New files added from book content (Problem-Free Diabetes + El Poder del Metabolismo)

---

## 🚀 How to Use This Repo

### Option 1 — Claude Project (Fastest)
1. Copy the entire contents of `system-prompt/metalibot_system_prompt_v5.md`
2. Paste into your Claude Project instructions
3. MetaliBot is live and bilingual

### Option 2 — API Integration
```javascript
const response = await fetch("https://api.anthropic.com/v1/messages", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    model: "claude-sonnet-4-20250514",
    max_tokens: 1000,
    system: METALIBOT_SYSTEM_PROMPT, // from system-prompt/metalibot_system_prompt_v5.md
    messages: [{ role: "user", content: userMessage }]
  })
});
```

### Option 3 — Inject Specific Knowledge
For targeted conversations, inject only the relevant knowledge file:
- Diabetes question → inject `14_diabetes_clinical_guide.md`
- Supplement question → inject `05_magnesium_potassium.md`
- Glossary lookup → inject `15_clinical_glossary.md`

---

## 🧩 Complete Knowledge Base Index

| # | File | Topic | Source |
|---|------|--------|--------|
| 1 | 01_plate_proportion_3x1.md | 3×1 Diet — food lists, proportions, cultural examples | Metabolic system |
| 2 | 02_food_aggressors_TAM.md | TAM framework, identification methods | Clinical observation |
| 3 | 03_candida_albicans.md | Candida — 22 symptoms, 78 toxins, protocol | Clinical research |
| 4 | 04_insulin_resistance.md | Insulin resistance — mechanism and reversal | Metabolic science |
| 5 | 05_magnesium_potassium.md | Magnesium citrate + potassium — complete guide | Clinical studies |
| 6 | 06_green_vegetable_juices.md | Green juices — exosome science, recipes | Research + clinical |
| 7 | 07_fatty_liver.md | Fatty liver — T4→T3 link, cleanse protocol | Clinical observation |
| 8 | 08_nervous_system_types.md | Excitado/Pasivo — personalized nutrition | Autonomic science |
| 9 | 09_medications_metabolism.md | Drug-metabolism interactions | Clinical education |
| 10 | 10_extreme_diets_hcg.md | HCG/crash diet dangers — muscle destruction | Metabolic science |
| 11 | 11_hydration.md | Water formula, dehydration-hunger connection | Clinical data |
| 12 | 12_coconut_oil_mct.md | MCT science, antifungal properties | Research |
| 13 | 13_core_beliefs.md | Foundational philosophy — body is perfect | Doctrine |
| 14 | **14_diabetes_clinical_guide.md** | **Full diabetes protocol — glucose targets, complications, prevention** | *Problem-Free Diabetes* |
| 15 | **15_clinical_glossary.md** | **50+ precise clinical definitions (A1c to Vasopressin)** | *Problem-Free Diabetes* |
| 16 | **16_el_poder_del_metabolismo_core.md** | **Core teachings: enemies, Mediterranean model, carb addiction** | *El Poder del Metabolismo* |
| 17 | **17_sugar_fructose_enemy.md** | **Sugar/HFCS science, the glucose-insulin-fat loop** | *El Poder del Metabolismo* |
| 18 | **18_hypothyroidism_temperature_test.md** | **Temperature test, T4→T3 pathway, goitrogens** | *El Poder del Metabolismo* |
| 19 | **19_stress_cortisol_weight.md** | **Cortisol = fat storage, adaptogens, sleep-metabolism link** | *El Poder del Metabolismo* |
| 20 | **20_research_bibliography.md** | **Full medical bibliography — 50+ referenced works** | *Problem-Free Diabetes* |

---

## 📺 Video Library

See `videos/video_reference_library.md` for 10 curated MetabolismoTV videos with topic routing logic.
Combined views: 690,000+. Top performer: ¿Porqué Tengo Verrugas? (344K views).

---

## 🌐 Key Resources

- Full video library (2,000+ videos): https://www.youtube.com/@MetabolismoTV
- NaturalSlim® system: https://us.naturalslim.com
- Natural health courses (UNIMETAB): https://www.unimetab.com
- Written articles: https://www.preguntaleafrank.com

---

## ⚖️ Disclaimer

This knowledge base is educational and based on metabolic science and clinical observation. It does not replace personalized medical advice. Always work with a qualified healthcare provider, especially if taking medications or managing a diagnosed condition.

---

*MetaliBot Knowledge Base v2.0 | March 2026*
*20 knowledge files · 2 books extracted · System prompt v5*
*"La verdad siempre triunfa."*
