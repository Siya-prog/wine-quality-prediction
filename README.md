# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the quality of wine based on its chemical characteristics such as acidity, density, pH, and alcohol content. It demonstrates a real-world application of machine learning in the field of viticulture.

---

## 🎯 Objectives
- Analyze chemical properties affecting wine quality  
- Perform exploratory data analysis (EDA)  
- Build and evaluate multiple classification models  
- Compare model performance and interpret results  

---

## 📊 Dataset
- Dataset Name: **WineQT.csv**  
- The dataset contains various physicochemical properties of wine samples.

### 🔬 Features Include:
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

### 🎯 Target Variable:
- **Quality** (score between 0–10)

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🤖 Machine Learning Models
The following classifiers were used:
- Random Forest Classifier  
- Stochastic Gradient Descent (SGD) Classifier  
- Support Vector Classifier (SVC)  

---

## 🔍 Exploratory Data Analysis
- Checked missing values and dataset structure  
- Visualized feature distributions  
- Generated correlation heatmap  
- Analyzed relationship between chemical features and quality  

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 🏆 Results
- Random Forest achieved the highest accuracy among all models  
- Key influencing features:
  - Alcohol  
  - Volatile Acidity  
  - Sulphates  

---

## 📷 Visualizations
- Correlation Heatmap  
- Feature vs Quality plots  
- Confusion Matrix  

(Add screenshots in the images folder and link them here)

---

## 🚀 How to Run the Project

1. Clone the repository:
   git clone https://github.com/your-username/Wine-Quality-Prediction.git

2. Navigate to the project folder:
   cd Wine-Quality-Prediction

3. Install dependencies:
   pip install -r requirements.txt

4. Run the notebook:
   - Open in Jupyter Notebook or Google Colab  
   - Upload the dataset if required  
   - Run all cells  

---

## 📁 Project Structure

Wine-Quality-Prediction/
│
├── data/
│   └── WineQT.csv
│
├── notebooks/
│   └── wine_quality.ipynb
│
├── images/
│   ├── heatmap.png
│   └── results.png
│
├── README.md
└── requirements.txt

---

## 📌 Conclusion
Machine learning techniques can effectively predict wine quality based on chemical properties. Among the models tested, Random Forest performed best due to its ability to capture complex relationships between features.

---

## 🔮 Future Improvements
- Hyperparameter tuning for better accuracy  
- Use advanced models like XGBoost  
- Convert into a web application using Streamlit  

---

## 📬 Contact
For any queries or suggestions, feel free to connect.

---

⭐ If you like this project, don't forget to give it a star!
