# Data-Centric-Machine-Learning-Framework-for-Heart-Stroke-Prediction
Built a data-driven machine learning pipeline to predict the likelihood of stroke in individuals using healthcare records. The framework emphasizes advanced data preprocessing and imbalance handling to improve clinical decision support.
•	Designed a complete stroke prediction pipeline with a focus on data integrity, quality, and preprocessing, enabling robust and reliable ML performance.
•	Implemented MICE (Multiple Imputation by Chained Equations) to accurately impute missing values by modeling conditional dependencies among all numeric features, preserving natural data variability.
•	Conducted distribution-based outlier detection using histograms and boxplots, followed by IQR-based filtering to remove extreme anomalies in features like avg_glucose_level and bmi, enhancing model generalization.
•	Performed thorough Exploratory Data Analysis (EDA) including correlation heatmaps, categorical feature countplots, and numeric feature histograms to uncover insights and guide feature selection.
•	Handled categorical variable encoding using OrdinalEncoder to transform qualitative health indicators (e.g., gender, work_type, smoking_status) into machine-readable formats.
•	Applied SMOTE (Synthetic Minority Over-sampling Technique) to address significant class imbalance (only ~5% stroke cases), allowing the model to learn from a balanced dataset and improving minority class recall.
•	Trained a Random Forest Classifier on the preprocessed dataset, leveraging its ensemble capabilities for high accuracy and interpretability.
•	Evaluated model performance using classification metrics (accuracy, precision, recall, F1-score), confusion matrix heatmaps, and ROC-AUC analysis, providing clear diagnostics for deployment-readiness.
•	Identified and visualized the top 10 most important features contributing to stroke prediction, aiding explainability and model transparency for clinical use.

Skills & Tools Used: Python, Pandas, Scikit-learn, Seaborn, Matplotlib, IterativeImputer (MICE), SMOTE, Random Forest, Ordinal Encoding, Data Cleaning, Outlier Removal, Feature Importance, Confusion Matrix, ROC-AUC, EDA, Healthcare DataModeling,heapmaps,histplots,boxplots 
