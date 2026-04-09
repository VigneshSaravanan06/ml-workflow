# ML Workflow Assignment

## Task 1

**Label Column:**  
The label column is `repeat_purchase_flag` because it represents the target variable we are trying to predict (whether a customer makes a repeat purchase within 30 days).

**Data Leakage Column:**  
The column `discount_used_on_repeat_order` would introduce data leakage because it contains information about the repeat purchase itself, which would not be available at the time of prediction.

---

## Task 2

**Step 1: Data Exploration and Cleaning**  
Before training a model, it is important to explore and clean the dataset (handling missing values, checking distributions, and identifying outliers) to ensure the data quality is suitable for modeling.

**Step 2: Feature Selection and Engineering**  
Selecting relevant features and possibly creating new ones helps improve model performance and prevents issues like overfitting or data leakage, ensuring the model learns meaningful patterns.

---