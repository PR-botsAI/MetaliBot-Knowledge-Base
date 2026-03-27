# 🧬 MetaliBot Knowledge Base

> **AI Health Education Guide** | Metabolic Science · Clinical Observation · Natural Health  
> Bilingual (English / Spanish) · Education-First · Empowerment-Driven

---

## What Is MetaliBot?

MetaliBot is an AI health education assistant grounded in metabolic science and clinical observation. It helps people understand how their metabolism works, why conventional dieting fails, and what the body truly needs to heal, lose fat, regain energy, and manage chronic conditions — naturally.

**Core truth:** *"Diets don't work if you don't fix your metabolism first."*  
**Core belief:** *"The body is perfect. When given the right conditions, it always heals."*  
**Core promise:** *"La verdad siempre triunfa."*

> ℹ️ **Attribution policy:** All knowledge in this repository is attributed to metabolic science, clinical observation, and peer-reviewed research — not to any individual person.

---

## 📁 Repository Structure

```
MetaliBot-Knowledge-Base/
├── README.md
├── system-prompt/
│   ├── metalibot_system_prompt_v6.md    ← USE THIS — paste into Claude Project
│   └── metalibot_system_prompt_v5.md    ← Legacy version
├── knowledge-base/                       ← 49 Wikipedia-depth topic files
└── videos/
    └── video_reference_library.md         ← 10 videos with routing logic
```

---

## 🚀 How to Use

### Option 1 — Claude Project (Fastest)
1. Copy the entire contents of `system-prompt/metalibot_system_prompt_v6.md`
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
    system: METALIBOT_SYSTEM_PROMPT, // from system-prompt/metalibot_system_prompt_v6.md
    messages: [{ role: "user", content: userMessage }]
  })
});
```

### Option 3 — Targeted Knowledge Injection
For specific conversations, inject only the relevant knowledge file as additional context.

---

## 🧩 Complete Knowledge Base — 49 Files

### Core Metabolic Doctrine (Files 01–20)

| # | File | Topic |
|---|------|-------|
| 01 | 01_plate_proportion_3x1.md | 3×1 Diet — food lists, proportions, cultural examples |
| 02 | 02_food_aggressors_TAM.md | TAM framework, glucometer test, elimination method |
| 03 | 03_candida_albicans.md | 22 symptoms, 78 toxins, protocol, warts connection |
| 04 | 04_insulin_resistance.md | Cell receptor mechanism, reversal protocol |
| 05 | 05_magnesium_potassium.md | 68% global deficiency, citrate form, dosing, conditions |
| 06 | 06_green_vegetable_juices.md | Exosome science (2016), recipes, juicer vs blender |
| 07 | 07_fatty_liver.md | T4→T3 link, liver cleanse, thyroid restoration |
| 08 | 08_nervous_system_types.md | Excitado/Pasivo — personalized nutrition |
| 09 | 09_medications_metabolism.md | Drug-metabolism interactions |
| 10 | 10_extreme_diets_hcg.md | HCG/crash diet dangers — muscle destruction mechanism |
| 11 | 11_hydration.md | Water formula, urine guide, dehydration-hunger link |
| 12 | 12_coconut_oil_mct.md | MCT science, antifungal properties |
| 13 | 13_core_beliefs.md | Foundational philosophy — body is perfect |
| 14 | 14_diabetes_clinical_guide.md | Full diabetes protocol, glucose targets, complications |
| 15 | 15_clinical_glossary.md | 50+ clinical definitions (A1c to Vasopressin) |
| 16 | **16_metabolic_doctrine_core.md** | **Core metabolic doctrine — 12 enemies, enemies list, Mediterranean model** |
| 17 | 17_sugar_fructose_enemy.md | HFCS, glucose-insulin-fat loop, carb addiction science |
| 18 | 18_hypothyroidism_temperature_test.md | Temperature test, T4→T3 pathway, subclinical hypothyroid |
| 19 | 19_stress_cortisol_weight.md | Cortisol = belly fat, adaptogens, sleep-metabolism triangle |
| 20 | 20_research_bibliography.md | Full medical bibliography — 50+ referenced works |

### Extended Health Science (Files 21–33)

| # | File | Topic |
|---|------|-------|
| 21 | 21_peptide_science.md | BPC-157, TB-500, Ipamorelin/CJC, AOD-9604, MOTS-c, 5 goal stacks |
| 22 | 22_intermittent_fasting.md | 16:8, 18:6, OMAD, 5:2, autophagy timing, IF+peptides synergy |
| 23 | 23_morning_protocols.md | ACV, cinnamon, cayenne, black pepper, lemon, ginger — full science |
| 24 | 24_natural_health_stacks.md | 5 goal-specific stacks combining all protocols |
| 25 | 25_wellness_shots_complete.md | Ginger, turmeric, wheatgrass, beetroot, tart cherry, elderberry |
| 26 | 26_omega3_fish_oil.md | ALA/EPA/DHA, omega-6:3 ratio, dosing by condition |
| 27 | 27_vitamin_d3_k2.md | Calcium traffic mechanism, Rotterdam study, cofactors |
| 28 | 28_gut_microbiome.md | 38 trillion organisms, 5R protocol, probiotics by strain |
| 29 | 29_sleep_optimization.md | Glymphatic detox, sleep stages, GH in deep sleep, supplement stack |
| 30 | 30_testosterone_natural.md | Testosterone crisis, destroyers, resistance training, supplement tiers |
| 31 | 31_womens_hormones.md | Estrogen dominance, PCOS-insulin, chocolate cravings mechanism |
| 32 | 32_nootropics_brain.md | Neurotransmitter systems, Lion's Mane NGF, Candida-acetaldehyde brain fog |
| 33 | 33_cold_heat_therapy.md | Brown fat, contrast therapy, sauna GH, red light therapy |

### Advanced & Longevity Science (Files 34–49)

| # | File | Topic |
|---|------|-------|
| 34 | 34_berberine.md | Nature's metformin — Berberine vs Metformin RCT, PCSK9, PCOS |
| 35 | 35_NAD_NMN_longevity.md | NAD+ decline with age, NMN vs NR, sirtuins, CoQ10 |
| 36 | 36_thyroid_iodine_complete.md | Full thyroid panel, rT3, halide competition, Hashimoto's, selenium |
| 37 | 37_breathwork.md | Box breathing, 4-7-8, Wim Hof Method, pranayama, HRV |
| 38 | 38_circadian_rhythm.md | SCN master clock, chrononutrition, meal timing, Satchin Panda research |
| 39 | 39_heavy_metals_detox.md | Mercury/lead/arsenic/cadmium, testing, chlorella+cilantro, sauna detox |
| 40 | 40_collagen_bone_broth.md | Types I/II/III, tendon loading protocol, bone broth recipe, glycine+sleep |
| 41 | 41_autophagy_complete.md | AMPK-mTOR switch, spermidine, rapamycin, Candida xenophagy |
| 42 | 42_inflammation_guide.md | Cytokines, NF-κB, omega-6 crisis, LPS from gut, anti-inflammatory stack |
| 43 | 43_adrenal_health.md | HPA axis, pregnenolone steal, cortisol stages, adrenal recovery |
| 44 | 44_ketogenic_diet.md | Virta Health study (60% T2D reversal), keto flu prevention, keto+metabolic |
| 45 | 45_exercise_metabolism.md | GLUT4 mechanism, Zone 2 cardio, HIIT, fasted walk, post-workout nutrition |
| 46 | 46_zinc_complete.md | 300+ enzymatic reactions, zinc+testosterone, zinc+quercetin antiviral |
| 47 | 47_natural_detox_protocols.md | Liver Phase 1/2, liver cleanse, milk thistle, TUDCA, lymphatic activation |
| 48 | 48_mineral_complete.md | Chromium, selenium, copper, iron, calcium, boron, silicon — complete |
| 49 | 49_fasting_mimicking_longevity.md | Valter Longo FMD, 5-day protocol, stem cell regeneration, longevity table |

---

## 📺 Video Library

See `videos/video_reference_library.md` for 10 curated videos with topic routing logic.
Combined views: 690,000+. Top: ¿Porqué Tengo Verrugas? (344K views).

---

## 🌐 Key Resources

- Full video library (2,000+ videos): https://www.youtube.com/@MetabolismoTV
- NaturalSlim® system: https://us.naturalslim.com
- Natural health courses (UNIMETAB): https://www.unimetab.com

---

## ⚖️ Disclaimer

This knowledge base is educational and based on metabolic science and clinical observation. It does not replace personalized medical advice. Always work with a qualified healthcare provider, especially if taking medications or managing a diagnosed condition.

---

*MetaliBot Knowledge Base v3.0 | March 2026*  
*49 knowledge files · System prompt v6 · No personal attributions*  
*"La verdad siempre triunfa."*
