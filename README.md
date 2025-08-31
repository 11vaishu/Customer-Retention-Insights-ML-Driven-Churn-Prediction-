**Customer Churn Prediction
Overview** - Built ML models to predict customer churn on the Telco dataset. Focused on maximizing recall to catch at-risk customers and uncover key churn drivers.

**Workflow**

Data Preprocessing: Cleaned dataset, encoded categorical features.

Models: Logistic Regression, Random Forest, XGBoost.

Tuning: Applied hyperparameter search + threshold adjustment for recall.

Visualization: Confusion matrices, ROC curves, feature importance.

**📊 Results**
Model	Recall (Churn=1)	Key Notes
Logistic Regression	~80%	Best at catching churners
Random Forest	~50%	Higher accuracy, lower recall
XGBoost	~68%	Balanced precision & recall

**🛠️ Tech Stack** - Python, Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
