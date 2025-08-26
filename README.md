---

# 🌸 Iris Flower Classification using ML

This project uses classic machine learning models to classify iris flowers into three species based on their physical features. The dataset contains **150 rows** and is sourced from Kaggle.

[🔗 View dataset on Kaggle](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

---

## 📌 Project Overview

* Performed automatic data profiling using `pandas_profiling` (`ydata_profiling`) to generate an HTML report.
* Label encoded the `species` column.
* Split data into features (`X`) and target (`y`), and then into training and testing sets.
* Trained and evaluated four classifiers:

  * **Decision Tree**
  * **Random Forest**
  * **Support Vector Classifier (SVC)**
  * **K-Nearest Neighbors (KNN)**

---

## 🧪 Model Performance

| Model         | Accuracy | F1 Score |
| ------------- | -------- | -------- |
| Decision Tree | 0.9333   | 0.9333   |
| Random Forest | 0.9333   | 0.9333   |
| SVC           | 0.9667   | 0.9665   |
| **KNN**       | **1.0**  | **1.0**  |

✅ **K-Nearest Neighbors** performed best with perfect scores.

---

## ⚙️ Libraries Used

* `pandas`
* `numpy`
* `sklearn` (Scikit-learn)
* `ydata_profiling` (`pandas_profiling`)

---

## 📂 How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/arshid/iris-flower-dataset) and place it in your working directory.
2. Run the script or notebook to:

   * Generate the profile report (`IRIS.html`)
   * Encode labels and split data
   * Train and evaluate models

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✍️ Author

* **Sagar Uppal**
* GitHub: Sagar-Uppal-26(https://github.com/Sagar-Uppal-26)

---
