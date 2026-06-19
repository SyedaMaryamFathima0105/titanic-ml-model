# Titanic Survival Prediction: Logistic Regression Analysis

**Domain**: Machine Learning | Binary Classification | Model Interpretability  
**Status**: Complete, Documented, Reproducible

## 🎯 Objective
Built an end-to-end ML pipeline to predict passenger survival on the Titanic dataset. Prioritized model interpretability over black-box accuracy to extract statistically meaningful insights from demographic features.

## 🔬 Technical Approach
**Model**: Logistic Regression — selected for transparent coefficient analysis in binary outcomes  
**Stack**: Python, Pandas, Scikit-learn | Executed in Google Colab  
**Pipeline**: Data ingestion → Null handling → One-hot encoding → Stratified train-test split → Model fitting → Coefficient interpretation

## 📊 Results & Statistical Inference
**Test Accuracy**: 81.0%

**Learned Feature Weights:**
1. **Sex_male: -2.59** → Strongest predictor. Being male decreased log-odds of survival by 2.59
2. **Pclass: 1.31** → Passenger class showed strong positive correlation with survival
3. **SibSp: -0.31** → Family size aboard had a slight negative impact

**Key Takeaway**: Model coefficients provide direct, interpretable odds ratios. This confirms and quantifies the historical "women and children first" protocol and class-based access to lifeboats.

## 🚀 Reproduce
Click `Open in Colab` → `Runtime` → `Run all` → Results print in final cells

## 🌱 Technical Roadmap
- Feature engineering: Impute `Age`, bin `Fare`, extract `Title` from names
- Model comparison: Benchmark Logistic Regression vs Random Forest vs XGBoost on interpretability-accuracy tradeoff  
- Visualization: Plot ROC curve and coefficient importance

---
*Demonstrates core ML competency: data preprocessing, supervised learning, statistical interpretation, and reproducible documentation.*
