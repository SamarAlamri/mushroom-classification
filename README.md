# 🍄 Mushroom Edibility Classification

## 📌 Project Overview
This project focuses on building a machine learning model to classify mushrooms as either **Edible** or **Poisonous** based on physical characteristics (cap shape, gill color, odor, etc.). The goal is to develop a reliable model that can assist in identifying toxicity to prevent mushroom-related health issues.

## 📂 Dataset
* **Source:** [Kaggle / UCI Machine Learning Repository]
* **Description:** The dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family.
* **Key Features:** Odor, Gill Size, Spore Print Color, Stalk Shape, etc.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn
* **Environment:** Jupyter Notebook

## 🤖 Models Used
We experimented with the following algorithms to compare performance:
1.  **Decision Tree Classifier**
2.  **Random Forest Classifier** (Full Features)
3.  **Random Forest Classifier** (After Dropping Top Features to test robustness)

## 📊 Results
Below is the performance summary based on our testing:

| Model | Accuracy | Precision (Weighted) | Recall (Weighted) | F1-Score (Weighted) |
| :--- | :--- | :--- | :--- | :--- |
| **Decision Tree** | **99.75%** | 1.00 | 1.00 | 1.00 |
| **Random Forest (Full Features)** | 99.51% | 1.00 | 1.00 | 1.00 |
| **Random Forest (Drop Top Features)** | 98.46% | 0.99 | 0.98 | 0.98 |

### 💡 Key Findings
* **Decision Tree** achieved the highest raw accuracy at **99.75%**, slightly outperforming the Random Forest model.
* **Random Forest (Full Features)** was extremely close behind at **99.51%**, demonstrating high reliability.
* Even after removing the most dominant features (feature selection), the **Random Forest** model maintained a strong accuracy of **98.46%**, proving the dataset's strong predictive power across multiple variables.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/mushroom-classification.git](https://github.com/YOUR-USERNAME/mushroom-classification.git)
