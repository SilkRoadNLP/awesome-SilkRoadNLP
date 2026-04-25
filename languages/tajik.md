# Tajik — NLP Resources

[← Back to main list](../README.md)

Tajik is the official language of Tajikistan, closely related to Persian and Dari. It presents particular computational challenges due to its multi-script nature — Tajik is written in **Cyrillic** (primary) and **Arabic** scripts, complicating the development of unified NLP tools. Despite being spoken by millions, computational resources for Tajik are extremely limited.

---

## Table of Contents

- [Transliteration & Script Bridging](#transliteration--script-bridging)
- [Lexical Resources](#lexical-resources)
- [Language Understanding & Evaluation](#language-understanding--evaluation)
- [Multilingual Coverage](#multilingual-coverage)

---

## Transliteration & Script Bridging

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Transformers for Bridging Persian Dialects: Transliteration Model for Tajiki and Iranian Scripts](https://aclanthology.org/2024.lrec-main.1459/) | SadraeiJavaheri, Asgari, Rabiee | 2024 | [![GitHub](https://img.shields.io/badge/GitHub-Code_&_Data-black?logo=github)](https://github.com/language-ml/Tajiki-Shahname) |

> Develops transliteration models to bridge Tajiki Persian (Cyrillic) and Iranian Persian (Arabic script) using a parallel corpus from the Shahnameh. Transformer and GRU-based models outperform GPT-3.5. Releases a digitized collection of Persian poetry spanning 1000 years in Tajiki script.

---

## Lexical Resources

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [TajPersLexon: A Tajik–Persian Lexical Resource and Hybrid Model for Cross-Script Low-Resource NLP](https://aclanthology.org/2026.silkroadnlp-1.4/) | Arabov | 2026 | |

> **TajPersLexon** is a bilingual lexical resource of 40,112 Tajik-Persian word/phrase pairs bridging Cyrillic and Perso-Arabic scripts. A hybrid transliteration and alignment model supports cross-script NLP tasks for these closely related but orthographically distant language varieties.

---

## Language Understanding & Evaluation

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [One Language, Three of Its Voices: Evaluating Multilingual LLMs Across Persian, Dari, and Tajiki on Translation and Understanding Tasks](https://aclanthology.org/2026.silkroadnlp-1.10/) | Arnob, Mahi | 2026 | |

> Evaluates multilingual LLMs across the three major varieties of Persian (Farsi, Dari, Tajik) using 240,000+ processed samples. Highlights variety-specific performance gaps.

---

## Multilingual Coverage

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Glot500: Scaling Multilingual Corpora and Language Models to 500 Languages](https://aclanthology.org/) | Imani et al. | 2023 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/cisnlp/Glot500) [![HuggingFace](https://img.shields.io/badge/🤗-Model-yellow)](https://huggingface.co/cis-lmu/glot500-base) |

> Glot500 is a large-scale multilingual model covering 500+ languages including Tajik. Notes that Tajik is written in multiple scripts, adding complexity to NLP processing.

---

> **Note:** Tajik NLP remains in its early stages. The cross-script challenge (Cyrillic vs. Arabic) is a fundamental barrier. Contributions are welcome. See [Contributing](../README.md#contributing).
