# Hi, I'm Ashwath M

M.Tech student in Artificial Intelligence and Data Science at Shiv Nadar University, Chennai. I build ML and GenAI
systems end to end, and I report results on leakage-free, held-out test sets.

## Projects

| Project | What it does | Held-out test result | Stack |
|---|---|---|---|
| [Smart Health: Diabetes Prediction](https://github.com/Ashwath-04/Smart-Health-Machine-Learning-Based-Smart-Diabetes-Prediction) | Stacking ensemble with leakage-safe SMOTE, SHAP explanations, FastAPI service and Streamlit UI. UG capstone with Badri Gopikrishna. | Recall 0.815, F1 0.693, ROC-AUC 0.821 | scikit-learn, XGBoost, CatBoost, Optuna, FastAPI, Docker |
| [Human Protein Atlas XAI](https://github.com/Ashwath-04/human-protein-atlas-xai) | 4-channel MobileNetV2 for 28-class protein localization on 31,072 microscopy images, with Grad-CAM, a FastAPI backend and a Next.js front end. | Macro F1 0.571, macro ROC-AUC 0.949 | PyTorch, Grad-CAM, FastAPI, Next.js |
| [Customer Churn Prediction](https://github.com/Ashwath-04/customer-churn-prediction) | Five tuned classifiers on 7,043 telecom customers, threshold chosen on out-of-fold predictions, SHAP. | ROC-AUC 0.848, recall on churners 72.5% | scikit-learn, XGBoost, SHAP |
| [Paddy Yield Prediction](https://github.com/Ashwath-04/Paddy-Yield-Prediction) | Regression on the UCI Paddy dataset with a leakage audit, Optuna tuning and SHAP. | R² 0.991 total yield, 0.496 per hectare | LightGBM, XGBoost, Optuna, SHAP |
| [Iris Classification](https://github.com/Ashwath-04/iris-classification) | Five classifiers compared with repeated stratified CV. | Accuracy 0.967 (SVM) | scikit-learn |

Every project repository has the same layout: `src/` for the code, `scripts/` to train and evaluate, `notebooks/`
with saved outputs, `tests/` run by GitHub Actions, and `reports/` with figures, metrics and logs. Datasets and
trained weights are not committed; each README says where to get the data.

### Other work

- **Hallucination-Resistant Multimodal Socratic Tutor** (SIH 2026, Team Jura Tempest): offline RAG tutor over NCERT
  textbooks with hybrid retrieval, BGE re-ranking and an evidence gate. Shortlisted in the SIH internal round.
- **ShukanHochi** (SNUC 2026 24-hour hackathon): gamified habit tracker; I set up the AWS backend (API Gateway with a
  Cognito JWT authorizer, Lambda, MongoDB Atlas). [Team repository](https://github.com/Nnik345/ShukanHochi)

## Skills

**GenAI and LLMs:** RAG, hybrid retrieval, re-ranking, tool-calling agents, LLM evaluation, Hugging Face Transformers, Ollama
**ML and DL:** PyTorch, scikit-learn, XGBoost, LightGBM, CatBoost, Optuna, SHAP, Grad-CAM
**Backend and data:** FastAPI, Neo4j, MongoDB Atlas, AWS (API Gateway, Lambda, Cognito), Docker, MLflow, Git

## Contact

[Portfolio](https://ashwath-04.github.io) · [LinkedIn](https://linkedin.com/in/ashwath-mohan) · ashwath.mohan.t@gmail.com
