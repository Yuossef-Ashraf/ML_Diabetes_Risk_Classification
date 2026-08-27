# Diabetes Risk Classification & Health Analytics - Architecture & Pipeline Design

```mermaid
graph TD
    DataInput[Raw CSV Dataset: diabetes_risk_dataset_text_labels.csv] --> Preproc[Data Cleaning & Column Transformer]
    Preproc -->|Numeric| Scaler[StandardScaler Normalization]
    Preproc -->|Categorical| Encoder[One-Hot Categorical Encoding]
    Scaler --> Split[Train/Test Stratified Split 80/20]
    Encoder --> Split
    Split --> Train[Model Training: Random Forest Classifier]
    Train --> Eval[Evaluation & Benchmarks]
    Eval --> Inference[Production Inference & CLI]
```

## Comparative Models Evaluated
- **Random Forest Classifier**
- **XGBoost**
- **Logistic Regression**
- **Support Vector Machine**
