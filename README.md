# 🛳️ Titanic - End-to-End ML Pipeline

### Project overview
A modular pipeline demonstrating preprocessing, feature engineering, and model training for the Titanic survival prediction problem. Implementations include logistic regression (with CV), decision trees (with visualization), Random Forest (with pipeline and GridSearchCV), and XGBoost (with parameter tuning and feature importance).

### Reproducibility
- Use `random_state=42` in all steps that accept it.
- Save fitted scalers/encoders with `joblib` or `pickle` if you want to reuse them.

### Next steps & improvements
- Add unit tests for preprocessing functions.
- Add a Makefile or task script (e.g., `run_all.sh`) to standardize experiments.
- Add Dockerfile or conda environment for reproducibility.
- Add model serialization & a small Flask/FastAPI service for inference.

---
