# mobile-price-prediction-ml

# Mobile Price Range Prediction & Feature Engineering

## 📌 Project Overview
This machine learning project builds a classification model to predict the price tier of mobile phones based on their internal hardware specifications. By analyzing features such as RAM, battery capacity, and processing power, the model categorizes devices into four distinct price segments (Low Cost, Medium Cost, High Cost, Very High Cost). 

Additionally, a modern '5G connectivity' feature was engineered to evaluate how next-generation network specs alter structural decision boundaries in automated device pricing.

## 🛠️ Tech Stack Used
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Scikit-Learn (Random Forest), Matplotlib, Seaborn

## 📊 Key Insights Found
* **RAM Dominance:** Feature importance scoring conclusively proves that Random Access Memory (RAM) holds the highest statistical weight in driving price segmentation.
* **The 5G Premium Factor:** The custom-engineered 5G feature quickly climbed to a high ranking position, demonstrating that cell connectivity modules act as prominent decision barriers when isolating premium hardware tiers.
* **Model Validation:** Instead of standard accuracy testing, the system relies on a localized classification report and a localized confusion matrix to clearly track classification error behavior across adjacent pricing brackets.

## 🚀 How to Run the Code
1. Upload the `train.csv` dataset into your Google Colab file directory.
2. Open the `Mobile_Price_Classifier.ipynb` notebook and execute all code blocks.
3. The script will train the Random Forest Classifier live and output both the class-by-class accuracy report and the hardware importance chart.
