# 🧠 Abusive Context Detection

This project aims to detect hate speech and offensive language in text using a combination of classical machine learning and deep learning approaches. We experiment with models such as RNN and a hybrid CNN-LSTM, and compare them with traditional classifiers like SVM, Logistic Regression, Random Forest, and XGBoost. The end goal is to provide a clean, explainable pipeline and a deployable Gradio interface.

---

## 📁 Project Structure

```

abusive-context-detection/
├── data/                  # Raw and cleaned datasets
├── image/
├── notebooks/             # EDA and experiments
├── src/
│   ├── preprocessing/     # Tokenization, lemmatization, text cleaning
│   ├── embedding/         # TF-IDF, Word2Vec, BERT
│   ├── models/            # RNN, classical models, CNN-LSTM
│   └── evaluation/        # Metrics and model comparison
├── app/                   # Gradio web app
├── tests/                 # Unit and integration tests
├── .github/workflows/     # CI/CD GitHub Actions
├── requirements.txt       # Dependencies
└── README.md              # Project overview

````

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/mariam-khediri/abusive-context-detection.git
cd abusive-context-detection

# Install dependencies
pip install -r requirements.txt

# Run preprocessing
python src/preprocessing/preprocess.py

# Launch Gradio interface (when ready)
python app/interface.py
````

---

## 🔧 Models Used

* **Traditional ML**: Logistic Regression, SVM, Random Forest, XGBoost
* **Deep Learning**: RNN, Hybrid CNN-LSTM

---

## 🧪 CI/CD Pipeline

* GitHub Actions runs:

  * Code quality checks (flake8)
  * Unit tests (pytest)
  * Future support for automated model training and deployment

---

## 📊 Dataset

* **Source**: [Kaggle - Hate Speech and Offensive Language Dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset/data)

---

## ✨ Future Plans

* Hyperparameter tuning
* Explainability with LIME/SHAP
* Hugging Face Space deployment

---



