---
title: GeneForgeLang
emoji: 🧬
colorFrom: indigo
colorTo: blue
sdk: gradio
sdk_version: "3.50.2"
app_file: app.py
pinned: true
---

# 🧬 GeneForgeLang: Symbolic-to-Sequence & Cross-Modality Biomolecular Design Toolkit

**GeneForgeLang** is a symbolic, generative language that allows scientists to design and interpret DNA, RNA, and protein sequences with unified syntax and AI support.

This toolkit enables:
- Generation of realistic proteins from symbolic design
- Translation of symbolic phrases across DNA ↔ RNA ↔ Protein
- Structured, human-readable and AI-trainable syntax
- Semantic equivalence across molecular layers

---

## 🚀 Features

| Module                      | Description |
|----------------------------|-------------|
| 🧠 Phrase → Protein         | Generate realistic protein sequences from symbolic phrases |
| 🔁 Transcode Across Molecules | Translate GeneForgeLang phrases between DNA, RNA, and Protein |
| 📚 Universal Grammar        | One structure to rule them all: motifs, domains, PTMs, splicing |
| 🧬 Compact Notation         | Prefixes, accents, and structural markers for efficiency |
| 🧠 AI-Ready Output          | Compatible with transformer-based models like ProtGPT2 |

---

## 🧪 Example Input Phrases

### DNA → RNA

```
~d:Prom[TATA]-Exon1-Intr1-Exon2
↓
:r:Cap5'-Ex1-Ex2-UTR3'
```

### RNA → Protein

```
:r:Ex1-Ex2
↓
^p:Dom(Kin)-Mot(NLS)
```

---

## ▶️ How to Use

1. Launch this app on Hugging Face or locally
2. Choose your input phrase and source/target modality
3. Get your translated output or generated protein

---

## 📁 Files

| File                  | Description |
|-----------------------|-------------|
| `app.py`              | Full Gradio app (all tabs) |
| `semillas.json`       | Seed dictionary |
| `transcoder.py`       | Script for DNA/RNA/protein conversion |
| `requirements.txt`    | Python dependencies |
| `README.md`           | This file |

---

## 🧠 Developed by

**Fundación de Neurociencias**  
MIT License

Join us in shaping symbolic bio-AI.
