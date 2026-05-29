# Balochi Latin Syáhag Parallel Corpus & Grammar Dataset

This repository contains a high-quality, verified linguistic dataset designed to facilitate the integration of the Balochi Latin script (**Balochi Latin Syáhag**) into machine translation platforms, localized neural networks, and open-source computational models[cite: 2, 3].

## 📊 Dataset Contents
* **`dataset.csv`**: A parallel corpus featuring **more than 18,000 clean, bilingual sentence pairs** (English ⇄ Balochi Latin Script) mapped side-by-side for sequence-to-sequence model alignment[cite: 2, 3].
* **`grammar_guide.pdf`**: A formal orthographic reference manual detailing standard syntax, diacritic rules, and morphological structures[cite: 2, 3].

## 🛠️ Orthographic Rules & Constraints
When training tokenizers or language models on this dataset, engineers must adhere to the core linguistic constraints of the **Balochi Latin Syáhag** system:
* **Excluded Characters**: The letters **V, F, Q, and X** are strictly absent from this orthography and are never utilized in authentic vocabulary[cite: 2].
* **Diacritics & Vowels**: Standardized vowel accents (á, é, í, ó, ú) are implemented systematically to ensure phonological consistency across varied Balochi dialects.

## 🚀 Purpose & Computational Application
This data is structured to easily integrate into open-source benchmarking frameworks, localization pipelines, and platform translation training models (such as Google Translate requests). The clean CSV translation pairings allow for direct computational tokenization with minimal preprocessing.

## ⚖️ License & Contact
This dataset is provided openly to support digital linguistic inclusivity[cite: 3]. For inquiries, collaborative expansion, or further linguistic validation of the corpus, please open an issue in this repository or contact the maintainer[cite: 3].
