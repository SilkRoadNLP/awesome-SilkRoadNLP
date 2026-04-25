# Multilingual & Cross-lingual Resources

[← Back to main list](../README.md)

Resources spanning multiple Iranian languages or bridging Iranian languages with other world languages.

---

## Table of Contents

- [Multi-variety Benchmarks](#multi-variety-benchmarks)
- [Parallel Corpora](#parallel-corpora)
- [Cross-lingual Semantic Similarity](#cross-lingual-semantic-similarity)
- [Multilingual Language Models](#multilingual-language-models)
- [Cross-variety Evaluation](#cross-variety-evaluation)

---

## Multi-variety Benchmarks

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [APARSIN: A Multi-Variety Sentiment and Translation Benchmark for Iranic Languages](https://aclanthology.org/2026.silkroadnlp-1.9/) | Jafari, Azin, Roodi, Dehghani Tafti, Ghadrdan, Vatankhahan Esfahani, Naebzadeh, Shahhosseini, Khan, Forghani, Namazi, Hashemi, Farsi, Osoolian, Mohammadi, Zare, Khan, Hussain, Zaki, Mohammadi, Bali, Ranjbar, Lefever, Hoste | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Benchmark-black?logo=github)](https://github.com/SilkRoadAparsin) |

> **APARSIN** is a large-scale benchmark covering **14 Iranic languages and dialects** for sentiment analysis and machine translation. It provides standardized evaluation protocols and baselines using state-of-the-art LLMs, addressing the critical lack of multi-variety resources for the Iranian language family.

---

## Parallel Corpora

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [JW300: A Wide-Coverage Parallel Corpus for Low-Resource Languages](https://aclanthology.org/) | Agic et al. | 2019 | [![HuggingFace](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/sentence-transformers/parallel-sentences-jw300) |

> **JW300** is a parallel corpus covering over 300 languages with around 100,000 parallel sentences per language pair on average. Includes coverage for some Iranian languages, though quality and completeness may vary across different language pairs.

---

## Cross-lingual Semantic Similarity

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [A Framework for the Construction of Monolingual and Cross-lingual Word Similarity Datasets](https://aclanthology.org/) | Camacho-Collados et al. | 2015 | |

> Provides Spanish and Farsi versions of the RG-65 word similarity dataset, plus 15 cross-lingual datasets for language pairs including English-Farsi, Spanish-French, Spanish-German, and English-Farsi. Inter-annotator agreements of 0.83 and 0.88 respectively in terms of Pearson correlation.

---

## Multilingual Language Models

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Glot500: Scaling Multilingual Corpora and Language Models to 500 Languages](https://aclanthology.org/) | Imani et al. | 2023 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/cisnlp/Glot500) [![HuggingFace](https://img.shields.io/badge/🤗-Model-yellow)](https://huggingface.co/cis-lmu/glot500-base) |

> Covers 500+ languages including several Iranian varieties. Particularly relevant for Tajik and other Iranian languages written in multiple scripts.

---

## Cross-variety Evaluation

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [One Language, Three of Its Voices: Evaluating Multilingual LLMs Across Persian, Dari, and Tajiki on Translation and Understanding Tasks](https://aclanthology.org/2026.silkroadnlp-1.10/) | Arnob, Mahi | 2026 | |
| [Translate With Care: Addressing Gender Bias, Neutrality, and Reasoning in Large Language Model Translations](https://aclanthology.org/) | Zahraei et al. | 2025 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/pardissz/Translate-With-Care) [![HuggingFace](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/PardisSzah/TWC) |

> The **Translate-with-Care** dataset comprises 3,950 challenging scenarios across six low- to mid-resource languages to assess translation systems' performance, revealing universal struggles with genderless content, gender stereotyping, and reasoning errors.
