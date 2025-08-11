# Decision-Trees-and-Random-Forests
Learn tree-based models for classification &amp; regression.
📌 Objective
The goal of this task is to understand Decision Trees and Random Forests for classification problems, learn how to control overfitting, interpret feature importance, and evaluate models using cross-validation.

📂 Dataset
I have used the Heart Disease Dataset from Kaggle:
Heart Disease Dataset

Rows: 303

Columns: 14 (features + target)

Target column: target (1 = Disease, 0 = No Disease)

🛠 Tools & Libraries
Python

Pandas, NumPy (Data Handling)

Matplotlib (Visualization)

scikit-learn (ML Models)

📜 Steps Implemented
1️⃣ Load & Explore Dataset
Checked data types, null values, and first few rows.

2️⃣ Data Preparation
Split into features (X) and target (y).

Train-test split (80% train, 20% test).

3️⃣ Decision Tree Classifier
Trained a basic Decision Tree.

Measured accuracy and generated a classification report.

Visualized the decision tree using plot_tree.

4️⃣ Control Overfitting
Trained a pruned Decision Tree with max_depth=4 to avoid overfitting.

5️⃣ Random Forest Classifier
Trained a Random Forest with 100 trees.

Compared accuracy with Decision Tree.

6️⃣ Feature Importance
Extracted and plotted feature importance from the Random Forest model.

7️⃣ Cross-Validation
Performed 5-fold cross-validation to check model stability.

📊 Results
Model	Accuracy
Decision Tree	~85%
Pruned Decision Tree	~83%
Random Forest	~90%

Random Forest outperformed the Decision Tree and provided more stable results.

📌 Key Learnings
Decision Trees are easy to interpret but prone to overfitting.

Random Forests reduce overfitting using bagging.

Feature importance helps in dimensionality reduction.

Cross-validation ensures the model generalizes well.

