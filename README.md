# Arabic Authorship Attribution

## Introduction
This project presents a robust and effective methodology for identifying the authors of Arabic texts. Our solution is built on traditional machine learning techniques, leveraging Term Frequency – Inverse
Document Frequency (TF-IDF) features at both the word and character levels.

This work was developed specifically for the **AraGenEval 2025 shared task** on Arabic authorship attribution. More information about the task and the associated paper can be found at the [Official AraGenEval 2025 Website](https://ezzini.github.io/AraGenEval/PAPER.html). Our system achieved highly competitive results while maintaining computational efficiency and interpretability compared to deep learning models.

## Key Features
* **Effective Feature Engineering:** The project combines word-level and character-level TF-IDF features to capture both semantic content and unique stylistic patterns of each author.
* **Traditional ML System:** Relies on proven algorithms like Logistic Regression and Linear SVM.
* **High Performance:** Our model achieved **88.90% accuracy** and an **82.74% Macro F1-score** on the official AraGenEval 2025 test set.
* **Interpretability:** By using traditional machine learning, the model's decisions are easier to understand and interpret.

## Methodology
Our methodology includes the following steps:
1.  **Arabic Text Preprocessing:** A comprehensive pipeline to clean texts, including removing non-Arabic characters and normalising whitespace.
2.  **Feature Extraction:** Building a feature vector that combines word-level TF-IDF (up to 15,000 features) and character-level TF-IDF (up to 5,000 features).
3.  **Model Training:** Several algorithms like Logistic Regression and Linear SVM were evaluated, and the best-performing one was selected.

## Results
| Metric | Validation Set | Official Test Set |
| :--- | :--- | :--- |
| Accuracy | 90.54% | 88.90% |
| Macro F1-score | 82.63% | 82.74% |
