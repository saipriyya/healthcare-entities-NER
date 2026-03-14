# healthcare-entities-NER
# Healthcare Entity Extraction (NER) Case Study

## 📌 Project Overview
This repository documents a Named Entity Recognition (NER) system developed to extract clinical entities (Medications, Diseases, Dosages) from unstructured medical notes.

> **Note:** The source code is currently stored in a private local environment. This documentation serves as a technical overview of the methodology and results.

## 🛠 Methodology
* **Data Cleaning:** Handled missing values and standardized medical acronyms using Python (Pandas).
* **Model Selection:** Utilized a pre-trained **SpaCy** transformer model specifically fine-tuned for biomedical text.
* **Validation Strategy:** Implemented a manual QA check on 200+ samples to verify extraction logic.

## 📊 Key Results
* **Precision:** 94% in identifying Medication names.
* **Recall:** 92% in identifying Disease symptoms.
* **Efficiency:** Reduced manual data entry time by approximately 60% for test datasets.

## 🧪 Quality Assurance (QA) Process
To ensure data integrity, the following tests were performed:
1. **Edge Case Testing:** Verified how the model handles misspelled medical terms.
2. **Logic Validation:** Ensured dosage amounts were correctly linked to the corresponding medication.
