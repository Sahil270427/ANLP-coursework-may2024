# Advanced Natural Language Processing (ANLP) Assignment

This repository contains coursework for the Advanced NLP assignment, which focuses on using transformer-based models to classify and analyze text data. The assignment works with a propaganda detection dataset in `.tsv` format.

---

## 📁 Contents

- `ANLP Code.ipynb` — Main notebook implementing the model pipeline
- `propaganda_train.tsv`, `propaganda_val.tsv` — Dataset files
- `ANLP Report.pdf` — Project report detailing methodology and results
- `ANLP Code HTML.html` — Rendered version of the notebook (for viewing)

---

## 🧠 Features

- Text preprocessing and tokenization
- Transformer-based modeling (e.g., BERT or RoBERTa)
- Training and fine-tuning on propaganda detection data
- Evaluation using precision, recall, and F1-score
- Visualization of performance metrics
- Input and output handling via `.tsv` files

---

## 🛠️ Requirements

- Python 3.8+
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `transformers` (HuggingFace)
  - `torch`
  - `matplotlib`
  - `seaborn` (optional)

---

## ⚙️ Setup Instructions

Set up a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
