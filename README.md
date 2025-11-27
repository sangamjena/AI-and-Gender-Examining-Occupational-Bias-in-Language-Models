# AI and Gender: Examining Occupational Bias in Large Language Models

This repository contains the dataset and supplementary material for the project **“AI and Gender: Examining Occupational Bias in Large Language Models.”**  
The study qualitatively investigates how five LLMs describe professional roles when prompted with **neutral, non-leading prompts**, and whether their responses implicitly assign gender stereotypes.

---

## 📌 Experiment Overview

| Component | Details |
|----------|---------|
| Number of occupations | **26** |
| Prompt templates per occupation | **3** |
| Models evaluated | **5** → ChatGPT, Gemini, Claude, Grok, DeepSeek |
| Total responses | **26 × 3 × 5 = 390** |

Each prompt was executed **once per model** in a **fresh conversation**, and all responses were stored **without editing, regeneration, or filtering**.

The study analyzes whether models assign gender when none is implied, using surface linguistic markers such as **"he / him / man"** and **"she / her / woman"**.  
Bias labels include: **Male, Female, Male & Female, Neutral**.

---

## 📂 Dataset

The complete dataset of **390 raw model responses** is provided in:

🔗 `normalized_models_clean.xlsx`  
https://github.com/sangamjena/AI-and-Gender-Examining-Occupational-Bias-in-Language-Models/blob/main/normalized_models_clean.xlsx

### Sheet description
| Sheet name | Description |
|-----------|-------------|
| `raw_wide` | One row per occupation, containing all 3 prompts and responses from all 5 LLMs |


---

## 📑 Research Paper

The full academic report includes:  
- Abstract  
- Introduction  
- Related Work  
- Methods  
- Experimental Setup  
- Results  
- Limitations  
- Conclusion & Way Forward  
- Appendix (with consolidated bias table)

---

## 🔍 Key Findings (Short Summary)

- **ChatGPT, Gemini, and Claude** consistently produced **neutral responses with no gender assignment.**
- **Grok and DeepSeek** frequently assigned gender despite neutral prompts:
  - **Male defaults** → technical & leadership roles (e.g., CEO, Pilot, Scientist)
  - **Female defaults** → caregiving & arts roles (e.g., Nurse, Teacher, Folk Dancer)
- Results show a clear divide between **alignment-focused** and **less-filtered** model behaviour.

---

## 🔧 Future Scope

Planned work includes:
- Expanding beyond 26 occupations
- Quantifying bias (not only qualitative coding)
- Studying additional demographic dimensions (e.g., age, culture, socioeconomic framing)
- Comparing outputs across model updates over time

---

## 📜 Citation

If you use this dataset or analysis, please cite:

