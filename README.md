📌 Objective

The objective of this task is to build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

📂 Dataset
Dataset Name: Bank Marketing Dataset
Source: UCI Machine Learning Repository
Provided Link:
https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203
File Used:
bank.csv (or bank-full.csv)
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
🔄 Workflow
1️⃣ Data Loading
Loaded dataset using Pandas
Used ; as separator
2️⃣ Data Cleaning
Checked for missing values
Dataset found mostly clean
Verified data types
3️⃣ Data Preprocessing
Converted categorical columns into numerical using Label Encoding
4️⃣ Feature Selection
Independent Variables → All columns except y
Target Variable → y (purchase decision)
5️⃣ Train-Test Split
Split dataset into:
80% Training Data
20% Testing Data
6️⃣ Model Building
Used DecisionTreeClassifier from Scikit-learn
Trained model on training data
7️⃣ Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report
📊 Results
✅ Model successfully predicts customer purchase behavior
✅ Achieved accuracy around 80% – 85% (may vary)
📈 Visualization
Confusion Matrix (Heatmap)
Feature Importance Graph
🧠 Key Insights
Customer behavior can be predicted using simple ML models
Features like:
Age
Job
Balance
Duration
have significant impact on prediction
Decision Trees are easy to interpret and visualize
🚀 Conclusion

In this task, we:

Built a Decision Tree Classifier
Performed data preprocessing & encoding
Evaluated model performance
Gained insights into customer decision-making patterns
