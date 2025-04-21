# 🤖 FINCHAT – Financial Advice Chatbot

FINCHAT is a multi-model chatbot that provides personalized financial insights using LLMs. It combines:

- 💬 LLaMA for financial Q&A
- 🧠 BERT for sentiment-aware responses
- 🏷️ BERT NER for identifying financial entities

This project was built as part of the EY Data Science Take-Home Challenge.

---

## 🔧 Technologies Used

- Python
- HuggingFace Transformers
- PyTorch
- Streamlit (optional frontend)
- Datasets: FiQA-2018, Financial PhraseBank, FinNER

---

## 📁 Project Structure

FINCHAT-Financial-Advice-Chatbot/

│

├── data/                         # Raw and processed datasets

│   ├── financial_phrasebank.txt

│   ├── fiqa_dataset/

│   └── finner_dataset/

│

├── notebooks/                   # Jupyter notebooks for development

│   ├── 01_data_preprocessing.ipynb

│   ├── 02_llama_finetuning.ipynb

│   ├── 03_bert_sentiment.ipynb

│   ├── 04_ner_training.ipynb

│   └── 05_pipeline_testing.ipynb

│

├── scripts/                     # Python scripts for reusable functions

│   ├── preprocessing.py

│   ├── llama_pipeline.py

│   ├── sentiment_classifier.py

│   ├── ner_extractor.py

│   └── app_utils.py

│

├── models/                      # Trained model files and checkpoints

│

├── app/                         # Streamlit app (optional)

│   └── streamlit_app.py

│

├── results/                     # Metrics, evaluation reports, charts

│   ├── metrics.json

│   ├── evaluation_plots/

│

├── README.md                    # Project overview and setup instructions

├── requirements.txt             # Dependencies

└── .gitignore                   # Ignore checkpoints, logs, etc.

---

## ✅ Setup

```bash
pip install -r requirements.txt
