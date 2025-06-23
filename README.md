# 📬 Spam Classification with Classical ML and Explainable NLP

A supervised machine learning project based on the **UCI Spambase dataset**, exploring traditional models (Lasso, SVM, XGBoost) with modern **interpretability techniques**, dimensionality reduction via **Multiple Factor Analysis**, and potential future extensions using **transformer-based embeddings** (e.g., BERT/GPT).

All credits for the data belong to Hopkins, M., Reeber, E., Forman, G., & Suermondt, J. (1999). Spambase [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C53G6X.
---

## 🧠 Project Highlights

- 📊 **Exploratory Data Analysis**: visual inspection, sparsity, skewness, feature correlation  
- 🧼 **Preprocessing**: normalization, removal of zero-variance & highly correlated predictors  
- 🧬 **Dimensionality Reduction**: applied **Multiple Factor Analysis** (MFA) to respect feature-block structure  
- 🤖 **Models**: Lasso, Linear SVM, and XGBoost with grid tuning via cross-validation  
- 📈 **Evaluation**: performance tested on a held-out set after careful tuning  
- 🔍 **Interpretability**: feature importance with `vip`, `pdp`, and `iml::FeatureImp`  
- 🧪 **Reproducible**: built with `tidymodels`, `tidyverse`, `patchwork`, and `quarto::revealjs`  

---