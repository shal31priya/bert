# Email Classification & PII Masking 📧

An intelligent system for classifying emails into custom categories (e.g. Incident, Request, Problem), with built-in detection and masking of Personally Identifiable Information.

---

## 🧩 Features

- **Email Classification**: Classifies emails into predefined categories using a fine-tuned NLP model (e.g. BERT/XLM-RoBERTa) :contentReference[oaicite:2]{index=2}.
- **PII Masking**: Automatically identifies and masks sensitive data (names, emails, phone numbers) :contentReference[oaicite:3]{index=3}.
- **API Interface**: Built using FastAPI (or Gradio) for easy integration and interactive testing :contentReference[oaicite:4]{index=4}.

---

## 📁 Tech Stack

- **Python 3.8+**
- **NLP/ML**: Hugging Face Transformers, scikit-learn, spaCy (for NER/masking) :contentReference[oaicite:5]{index=5}
- **Tools**: FastAPI or Gradio, uvicorn
- **Utilities**: regex, pandas, joblib

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/email-classifier.git
cd email-classifier
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
