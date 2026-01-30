# Exoplanet Detection with Machine Learning 🚀

This project implements an end-to-end machine learning pipeline to classify whether a star hosts an exoplanet, using NASA’s Kepler light curve dataset.

# ⚙️ Features

Data preprocessing & feature engineering: cleaning raw Kepler data, handling missing values, constructing features from light curves.

Model training & evaluation: applied scikit-learn classifiers (Logistic Regression, Random Forest, etc.) to distinguish exoplanet-hosting vs non-exoplanet stars.

Performance metrics: compared models with accuracy, ROC curves, and confusion matrices.

Reproducibility: modular pipeline design with clear steps for ingestion, training, and evaluation.

# 📊 Results

Models achieved high accuracy in distinguishing exoplanet vs non-exoplanet signals.

KNN provided the best trade-off between interpretability and predictive power.

Evaluation included ROC/AUC analysis and confusion matrix visualization.

# 🚀 Getting Started
1. Clone the repo
git clone https://github.com/sathyas27/Exoplanet_Detection.git
cd exoplanet-detection

2. Set up environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt

3. Run the notebook

Open Jupyter Lab/Notebook and explore:

jupyter notebook notebooks/exoplanet-detection.ipynb

# 🛠 Tech Stack

Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Jupyter Notebook for interactive development

Astrophysical dataset from NASA Kepler mission

# 📌 Future Improvements

GitHub Actions + pytest to automate retraining and testing.

Explore deep learning models (e.g., CNNs for raw light curve classification).

# 📖 References

NASA Kepler Mission

Scikit-learn Documentation

# 👤 Author

Sathya Selvam
Computer Science @ University of Maryland
