# Takhayyul.AI : AI-Powered Roman Urdu Poetry Generator

Takhayyul.AI is an end-to-end NLP project that scrapes Roman Urdu poetry, trains a neural network to generate original verses, and deploys it using a simple web interface via Gradio or Streamlit.

---

## 📌 Features

- ✅ Scrapes Roman Urdu poetry from [rekhta.org](https://rekhta.org)
- ✅ Trains a character-level RNN/LSTM/GRU to learn poetic structure and rhythm
- ✅ Generates custom poetry based on user-provided starting prompts
- ✅ Deploys with Gradio or Streamlit for real-time interaction
- ✅ Fully open-source, reproducible, and beginner-friendly

---

## 🧠 Model

The core model is a **character-level LSTM** (can be replaced with GRU/RNN). It learns sequences of Urdu words written in Roman script and generates new poetic verses, preserving meter and emotional tone.

---

## 🚀 Deployment

### Option 1: Gradio

```bash
pip install -r requirements.txt
cd app
python poetry_py.ipynb

