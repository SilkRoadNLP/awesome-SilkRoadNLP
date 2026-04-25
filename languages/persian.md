# Persian (Farsi) — NLP Resources

[← Back to main list](../README.md)

Persian (Farsi) is the official language of Iran with over 70 million native speakers. It is also widely understood in Afghanistan (as Dari) and Tajikistan (as Tajik). Among Iranian languages, Persian has received the most comprehensive coverage in computational linguistics research.

---

## Table of Contents

- [Language Models](#language-models)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Hate Speech & Content Moderation](#hate-speech--content-moderation)
- [Sentiment Analysis & Social Computing](#sentiment-analysis--social-computing)
- [Parsing & Syntax](#parsing--syntax)
- [Machine Translation](#machine-translation)
- [Speech Processing](#speech-processing)
- [Semantic Similarity](#semantic-similarity)
- [Datasets & Corpora](#datasets--corpora)
- [Punctuation & Text Processing](#punctuation--text-processing)
- [Figurative Language & Pragmatics](#figurative-language--pragmatics)

---

## Language Models

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [ParsBERT: Transformer-based Model for Persian Language Understanding](https://aclanthology.org/) | Farahani et al. | 2020 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/hooshvare/parsbert) [![HuggingFace](https://img.shields.io/badge/🤗-Model-yellow)](https://huggingface.co/HooshvareLab/bert-base-parsbert-uncased) |
| [Unmasking the Factual-Conceptual Gap in Persian Language Models](https://aclanthology.org/2026.silkroadnlp-1.1/) | Sakhaeirad, Ma'manpoosh, Hemmat | 2026 | [![HuggingFace](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/divanbench/divanbench) |
| [Do Large Language Models Understand Double Mismatches? Evidence from Farsi](https://aclanthology.org/2026.silkroadnlp-1.3/) | Mohammadi | 2026 | |

> **ParsBERT** is a monolingual BERT model specifically trained on a large Persian dataset. It achieves state-of-the-art performance on sentiment analysis, text classification, and named entity recognition, outperforming multilingual alternatives for Persian.

> **DivanBench** is a manually curated benchmark of 315 questions across factual retrieval, paired scenario verification, and situational reasoning — designed to probe cultural and conceptual knowledge in Persian LLMs.

---

## Benchmarks & Evaluation

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [PMWP: A Benchmark for Math Word Problem Solving in Persian](https://aclanthology.org/2026.silkroadnlp-1.8/) | Abdolmaleki, Shamsfard, Hoste, Lefever | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Dataset-black?logo=github)](https://github.com/marzieh-abdolmaleki/PMWP) |

> **PMWP** is the first dataset of 15,000 elementary-level Persian math word problems for training and evaluating mathematical reasoning in LLMs.

---

## Hate Speech & Content Moderation

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Spanning the Spectrum of Hatred Detection: A Persian Multi-Label Hate Speech Dataset with Annotator Rationales](https://aclanthology.org/) | Delbari et al. | 2024 | [![GitHub](https://img.shields.io/badge/GitHub-Dataset_&_Code-black?logo=github)](https://github.com/Zahra-D/Phate) |
| [Culture Matters in Toxic Language Detection in Persian](https://aclanthology.org/) | Bokaei et al. | 2025 | |
| [Benchmarking Offensive Language Detection in Persian and Pashto](https://aclanthology.org/2026.silkroadnlp-1.2/) | Bokaei, Webber, Magdy | 2026 | |

> **Phate** consists of over 7,000 manually-annotated Persian tweets across hate, vulgarity, and violence categories. Each annotation specifies the targeted group and includes a rationale span. Available at [github.com/Zahra-D/Phate](https://github.com/Zahra-D/Phate).

---

## Sentiment Analysis & Social Computing

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Online Polarization Detection in Persian (Farsi) Social Media](https://aclanthology.org/2026.silkroadnlp-1.6/) | Davoudi, Goharian | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/dsaeedeh/Polarization_Detection) |

---

## Parsing & Syntax

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [On the Importance of Ezafe Construction in Persian Parsing](https://aclanthology.org/) | Nourian et al. | 2015 | |

> Manual annotation of Ezafe tags in Persian dependency treebanks achieves high annotator agreement and leads to 12.8% relative error reduction in dependency parsing and 31% relative error reduction in shallow parsing. Includes an open-source rule-based dependency to chunk converter.

---

## Machine Translation

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Multi-modal Neural Machine Translation for Low-Resource Classical Persian Poetry: A Culture-Aware Evaluation](https://aclanthology.org/2026.silkroadnlp-1.14/) | Ansari, Boukadoum, Sadat | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Corpus-black?logo=github)](https://github.com/amnghd/Persian_poems_corpus) |
| [Translate With Care: Addressing Gender Bias, Neutrality, and Reasoning in Large Language Model Translations](https://aclanthology.org/) | Zahraei et al. | 2025 | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/pardissz/Translate-With-Care) [![HuggingFace](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/PardisSzah/TWC) |
| [Transonics: A Practical Speech-to-Speech Translator for English-Farsi Medical Dialogs](https://aclanthology.org/) | Belvin et al. | 2005 | |

> The **Translate-with-Care (TWC)** dataset comprises 3,950 challenging scenarios across six low- to mid-resource languages to assess translation systems' performance on gender bias, neutrality, and reasoning.

> The Classical Persian Poetry NMT system introduces a parallel Persian-English corpus of 26,571 aligned verse pairs from Masnavi-ye-Ma'navi with audio recitations and a culture-specific evaluation framework.

---

## Speech Processing

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Segmentation Strategy Matters: Benchmarking Whisper on Persian YouTube Content](https://aclanthology.org/2026.silkroadnlp-1.13/) | Iranmanesh, Ziaei, Garman | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Dataset_&_Code-black?logo=github)](https://github.com/ri164-bolleit/persian-youtube-whisper-benchmark) |

> Benchmarks OpenAI's Whisper on 10 hours of Persian YouTube audio with gold-standard transcripts, showing that segmentation strategy has substantial impact on WER.

---

## Semantic Similarity

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [A Framework for the Construction of Monolingual and Cross-lingual Word Similarity Datasets](https://aclanthology.org/) | Camacho-Collados et al. | 2015 | |

> Farsi versions of the RG-65 word similarity dataset with inter-annotator agreement of 0.88 Pearson correlation, plus 15 cross-lingual datasets for pairs including English-Farsi.

---

## Datasets & Corpora

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [ParsCORE: The Persian Corpus of Online Registers](https://aclanthology.org/2026.silkroadnlp-1.7/) | Razzaghi, Henriksson, Laippala | 2026 | [![GitHub](https://img.shields.io/badge/GitHub-Dataset-black?logo=github)](https://github.com/TurkuNLP/ParsCORE) |

> **ParsCORE v0.1** is a corpus of 2,000 human-annotated Persian web documents spanning diverse online registers, developed within the Universal Register framework.

---

## Punctuation & Text Processing

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [PersianPunc: A Large-Scale Dataset and BERT-Based Approach for Persian Punctuation Restoration](https://aclanthology.org/2026.silkroadnlp-1.11/) | Ranjbar Kalahroodi, Faili, Shakery | 2026 | |

> **PersianPunc** is a dataset of 17 million samples for punctuation restoration. A fine-tuned ParsBERT model achieves 91.33% macro-F1.

---

## Figurative Language & Pragmatics

| Paper | Authors | Year | Links |
|-------|---------|------|-------|
| [Metaphors in Pre-Trained Language Models: Probing and Generalization Across Datasets and Languages](https://aclanthology.org/) | Aghazadeh et al. | 2022 | |
| [A Computational Approach to Language Contact — A Case Study of Persian](https://aclanthology.org/2026.silkroadnlp-1.5/) | Basirat, Namazifard, Baradaran Hemmati | 2026 | |

> The language contact study proposes a computational framework for detecting and quantifying lexical borrowing and phonological adaptation in Persian from Arabic, French, and English.
