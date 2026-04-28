# Hi, I'm Muhammad Danu Firjatullah Rachman 👋

I'm a **fresh graduate** transitioning into data science — building projects that turn raw data into decisions.

Currently focused on **e-commerce analytics**, **machine learning**, and **NLP**. All projects are end-to-end: from messy data to deployed models.

---

## 🚀 Featured Projects

### 📦 E-Commerce Sales Analysis (Olist)
> End-to-end analysis of 100K+ transactions from Brazil's largest e-commerce platform

- Identified that delivery delays >14 days drop average customer rating by **58%**
- Built a **Random Forest classifier** (AUC 0.856) to predict customer satisfaction from order data
- Segmented 96K customers into 4 behavioral groups using **RFM + K-Means clustering**
- **Stack**: Python · pandas · scikit-learn · matplotlib · seaborn

🔗 [[View Repository](https://github.com/DANUFR17/ecommerce-sales-analysis)]

---

### 🏠 House Price Prediction (Ames Housing)
> End-to-end ML pipeline — feature engineering, ensemble stacking, SHAP interpretability, Streamlit deployment
 
- Reduced prediction error from **~$29K** (Linear Regression) to **~$17K** (Stacking) — **36% improvement**
- Built **model stacking** (Ridge + Lasso + XGBoost + LightGBM) with out-of-fold prediction to prevent data leakage
- Applied **SHAP TreeExplainer** to explain individual predictions — feature I created (`TotalSF`) ranked #1 globally
- Deployed as interactive **Streamlit app** with real-time SHAP waterfall visualization
- **Stack**: Python · XGBoost · LightGBM · SHAP · Streamlit · scikit-learn

🔗 [[View Repository](https://github.com/DANUFR17/house-price-prediction)]

---

### 🐦 Twitter Sentiment Analysis
> 4-phase project: from EDA and classical ML to deep learning and live deployment
 
Built on the **Sentiment140 dataset (1.6M tweets)**, this project demonstrates the full ML lifecycle — exploratory analysis, MLOps-grade training, deep learning, and production deployment.
 
#### Phase 1 — Baseline
- Built text preprocessing pipeline: URL/mention removal, stopword filtering, tokenization
- Achieved **79% accuracy** with TF-IDF + Logistic Regression on 50K tweets
- Visualized most influential words per class using wordcloud and coefficient analysis
#### Phase 2 — Rich EDA & MLOps Pipeline
- Conducted temporal analysis (sentiment by hour), top-user breakdown, and bigram/trigram analysis
- Replaced single train/test split with **5-fold stratified cross-validation** for more reliable evaluation
- Plotted **learning curves** to diagnose underfitting/overfitting
- Used **GridSearchCV** to tune TF-IDF + LR hyperparameters (C, max_features, ngram range) — visualized results as a heatmap
#### Phase 3 — Deep Learning
- Built a **BiLSTM** (Keras) with global average + max pooling, EarlyStopping, and ReduceLROnPlateau
- Integrated **`cardiffnlp/twitter-roberta-base-sentiment`** via HuggingFace Hub — a RoBERTa model pretrained on 58M tweets, chosen for domain match over fine-tuning from scratch
- Benchmarked all 4 models (NB, LR, BiLSTM, RoBERTa) on accuracy, F1, and inference latency
#### Phase 4 — Deployment
- Built a **Streamlit app** with single-tweet and bulk analysis tabs, confidence gauge, pie chart, and CSV export
- Built a **FastAPI backend** with `/predict`, `/predict/bulk`, and `/health` endpoints, Pydantic validation, and auto-generated Swagger docs
**Stack**: Python · NLTK · scikit-learn · TensorFlow · PyTorch · HuggingFace Transformers · FastAPI · Streamlit · Plotly

🔗 [[View Repository](https://github.com/DANUFR17/project-sentiment)]

---

## 🛠️ Tech Stack

**Languages & Data**
```
Python · SQL · pandas · NumPy
```

**Machine Learning**
```
scikit-learn · XGBoost · K-Means · Logistic Regression · Random Forest
```

**Deep Learning & NLP**
```
TensorFlow · PyTorch · HuggingFace Transformers · BiLSTM · RoBERTa · NLTK · TF-IDF
```
 
**Deployment**
```
FastAPI · Streamlit · REST API · Swagger
```
 
**Visualization & Tools**
```
matplotlib · seaborn · Plotly · Git · GitHub · VSCode · Kaggle · Jupyter Notebook
```

**Tools**
```
Git · GitHub · VSCode · Kaggle
```

---

## 📈 What I'm Currently Working On

- Deploying the Olist satisfaction predictor as a live **Streamlit app**
- Practicing **SQL window functions** for analytics interview prep
- Exploring **time series forecasting** with Prophet

---

## 📫 Let's Connect

- 💼 [[LinkedIn](https://www.linkedin.com/in/muhammad-danu-firjatullah-rachman-740102261/)]
- 📧 muhammaddanufirjatullahrachman@gmail.com

---

*All projects include full notebooks, clean README, and reproducible code.*
