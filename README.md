# 🧠 Mental Health Risk Classification: Decision Tree Approach

## 🌟 Project Overview
Mental health is a key part of overall well-being. Early identification of individuals at risk helps healthcare providers allocate resources and design targeted interventions. This project predicts **mental health risk levels** (High, Medium, Low) using psychological and lifestyle features, applying a full data science workflow from cleaning and encoding to modeling, evaluation, and actionable insights.

## 🎯 Objectives
- Analyze relationships between key features and mental health risk.
- Build an interpretable decision tree model for classification.
- Optimize model generalization through pruning.
- Extract actionable insights to support early intervention and resource allocation.

## 🛠️ Key Skills & Techniques
Decision Tree Modeling, Hyperparameter Tuning (Pruning), Feature Importance Analysis, Classification Metrics & Model Evaluation, Data Preprocessing & Encoding, Exploratory Data Analysis (EDA) & Visualization, Actionable Insights

## 🧰 Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 📊 Workflow
1. **Data Preprocessing**: Handle missing values, encode categorical features, split data with stratification.
2. **Exploratory Data Analysis (EDA)**: Visualize distributions, correlations, and relationships.
3. **Modeling**: Train Decision Tree Classifier, tune `max_depth` and `min_samples_split` for pruning.
4. **Evaluation**: Accuracy, confusion matrix, classification report.
5. **Insights**: Identify key predictors and highlight high-risk individuals for interventions.

## 📈 Visualizations
- Feature Importance Plot: Top predictors (Depression & Anxiety Scores).  
- Decision Tree Structure: Pruned, interpretable tree.  
- Confusion Matrix: Correct vs. misclassified risk levels.

## 📈 Key Insights
- **Primary Risk Drivers:** Depression and anxiety scores strongly predict mental health risk; interventions should prioritize these factors.  
- **Model Reliability:** Pruning experiments demonstrated how tree depth affects overfitting vs. generalization, confirming medium-depth trees strike the right balance.  
- **Practical Application:** Model can support early screening, targeted interventions, and resource allocation in healthcare settings.  
- **Future Opportunities:** Ensemble models (Random Forest, Gradient Boosting) and advanced feature engineering (interactions like stress × sleep) could capture more complex risk patterns.


## 📂 Repository Contents
- `KM_Leshike_Decision_Tree.ipynb` - Jupyter Notebook with full analysis.  
- `mental_health_dataset.csv` - dataset features.  

