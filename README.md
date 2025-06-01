# Data-Assessment-

# Customer Purchase Prediction – Agricultural Products

## 📌 Project Overview
This project aims to predict whether a customer will purchase a product again based on previous purchase data. The dataset includes sales of agricultural products such as fertilizers, seeds, and weedicides across different regions of Ghana.

## 📂 Dataset Summary
- **Rows:** 300
- **Columns:** 10
- **Key Fields:** Product, Category, Quantity, Unit Price (GHS), Customer Region, PurchasedAgain

## 🎯 Objective
To build a classification model that predicts if a customer will **purchase again** (`Yes` or `No`) using customer behavior, product type, pricing, and regional data.

## 🧹 Data Preprocessing
- Handled missing values using forward/backward fill.
- Created new date-related columns: `OrderDay`, `OrderMonth`, `OrderYear`.
- Standardized categorical entries in `Product` and `CustomerRegion` columns (e.g., removing inconsistencies like "maize", "MAIZE", "maize").
- Dropped unnecessary columns like `OrderDate`.


## 🤖 Modeling
Used `RandomForestClassifier` 

### 📈 Evaluation Metrics
- **Accuracy**: 50%
- **Precision**: 52.94%
- **Recall**: 81.82%
- **F1 Score**: 64.29%

Despite the **small dataset size (300 rows)** and **class imbalance**, the model showed promising recall performance. 



## 📝 Conclusion
- **Asaase Wura** is the most frequently purchased product.
- **Fertilizers** dominate the product category.
- **Ashanti region** records the highest number of customers.
- The model performs moderately, with a strong **recall**, suitable for minimizing false negatives (i.e., not missing likely repeat customers).

## 💡 Recommendations
- Further improve prediction by:
  - Collecting more data to train deeper models.

## 👨‍💻 Author
- Benedicta Mankata
- Data Analyst | Machine Learning 

