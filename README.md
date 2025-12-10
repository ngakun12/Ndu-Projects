# Ndu Projects — Data Analytics & Applied ML Portfolio

This repository is a curated portfolio of analytics and machine learning projects spanning NLP, time series, and applied business analysis. Each project folder includes code, notes, and (where available) a short write-up describing the approach and results.

## Quick links
- **LinkedIn:** https://www.linkedin.com/in/ngakun12/
- **GitHub:** https://github.com/ngakun12

---

## Featured projects (recommended starting points)

| Project | What it is | Core skills | Artifacts |
|---|---|---|---|
| **Dark Jargon Classifier** | NLP classifier for detecting coded/jargon language (domain-specific text classification). | Python, NLP, feature engineering or transformers, model evaluation | `README`, notebook/scripts, metrics (F1/PR-AUC), error analysis |
| **Machine Learning Cyberbullying BERT detection** | Transformer-based text classification for harmful content detection. | BERT/Transformers, PyTorch, preprocessing, evaluation | `README`, training/eval code, confusion matrix, sample predictions |
| **Healthcare readmission time series analysis** | Time-series analysis/forecasting for healthcare utilization/readmission-related signals. | Time series, EDA, modeling, backtesting | `README`, plots, forecast metrics (MAE/RMSE), methodology notes |

> Tip: Replace the “Artifacts” column items with direct links to the notebook/report inside each folder once you add them.

---

## Project index

### NLP / Text
- **Dark Jargon Classifier**
- **Machine Learning Cyberbullying BERT detection**
- **Speaker Diarization project** (audio/speech analytics)

### Analytics / Case studies
- **Bank Case Study — customer demographics & retention signals**
- **Car data science portfolio**

### Healthcare / Time series
- **Healthcare readmission time series analysis**

---

## How to run (general)
Most projects are in Python. If a project includes a `requirements.txt` or `environment.yml`, run from that folder:

### Option A — venv + pip
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
