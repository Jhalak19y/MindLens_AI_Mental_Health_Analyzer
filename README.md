# 🧠 MindLens: AI-Powered Mental Health & Mood Analyzer

MindLens is a data-driven tool built to analyze emotional and mental health expressions using **AI**, **NLP**, and **data visualization**.  
It predicts **sentiment** and **emotions** from text (like social media posts, journal entries, or public datasets), while also allowing users to track their **daily moods** over time.

---

## 📌 Key Features

- ✅ Clean and preprocess raw text for analysis
- ✅ Perform **Sentiment Analysis** using TextBlob (`Positive`, `Neutral`, `Negative`)
- ✅ Predict **Emotions** using a fine-tuned HuggingFace `distilRoBERTa` model
- ✅ Input and log your **daily mood entries**
- ✅ Merge emotion data + mood logs
- ✅ Visualize trends with:
  - WordCloud
  - Sentiment distribution
  - Mood-over-time graph
- ✅ Export to `.csv` for further exploration

---

## 📊 Technologies Used

- **Python** (Colab)
- **Pandas**, **Matplotlib**, **Seaborn**
- **TextBlob**, **NLTK**
- **Transformers (HuggingFace)**
- **WordCloud**, **TQDM**

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `MindLens_AI_Mental_Health_Analyzer_Final.ipynb` | Cleaned, final Colab notebook |
| `requirements.txt` | Python libraries used |
| `README.md` | This file |
| `MindLens_Final_Merged_Data.csv` | ⛔ Large file – [Download from Google Drive](https://drive.google.com/your-shared-link) or use sample below |

---

## 🚀 Getting Started

```bash
# Clone this repo
git clone https://github.com/your-username/MindLens-Mental-Health-Analyzer.git
cd MindLens-Mental-Health-Analyzer

# Install dependencies
pip install -r requirements.txt

# Run the notebook in Jupyter or Colab
