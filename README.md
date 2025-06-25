# Sentiment Analysis Comparison

This project compares sentiment analysis results using two different NLP models: **VADER** (Valence Aware Dictionary for Sentiment Reasoning) and **RoBERTa** (a transformer-based model from HuggingFace). The goal is to analyze and visualize how these models interpret sentiment across a large dataset of Amazon Fine Food Reviews.

---

## 📁 Project Structure

- `sentimental_analysis_comparison.ipynb` – Main Jupyter notebook with the complete analysis, visualizations, and model comparisons.
- Dataset: [Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)

---

## 🔍 Key Features

- **Data Loading & Preprocessing**  
  Loads the Amazon Fine Food Reviews dataset and performs basic cleaning.

- **Sentiment Analysis with VADER**  
  Applies VADER sentiment scoring to the review text.

- **Sentiment Analysis with RoBERTa**  
  Utilizes the `cardiffnlp/twitter-roberta-base-sentiment` model for transformer-based sentiment scores.

- **Comparative Visualizations**  
  Barplots and statistical breakdowns of sentiment scores across different review ratings.

- **Merged Analysis**  
  Combines both models’ outputs for side-by-side performance evaluation.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- HuggingFace Transformers
- NLTK (VADER)
- Scipy (Softmax)

---

## 📊 Example Output

- Distribution of VADER and RoBERTa scores across `1-5 star` reviews.
- Comparison of positive/neutral/negative percentages from both models.
- Visual confirmation of model tendencies (e.g., RoBERTa being stricter with positivity).

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
