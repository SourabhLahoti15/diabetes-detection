# 🩺 Diabetes Detection Project
Welcome to the Diabetes Detection project — an end-to-end data analysis workflow using a clinical dataset from Kaggle. The goal is to understand and visualize trends that can help identify diabetic patients based on various health indicators.


# 📁 Project Structure
diabetes-detection/  
├── dataset/  
│   └── 100000-diabetes-clinical-dataset.csv  
├── notebook/  
│   └── DiabetesDetection.ipynb  
├── powerbi/  
│   └── diabetesDetection.pbix  
├── presentation/  
│   └── Diabetes-Detection-with-Data-Analytics.pdf  
├── README.md  
└── requirements.txt  


# ⚙️ Setup Instructions
## ✅ Requirements
## Core libraries
pandas==2.2.2  
numpy==1.26.4  
## Visualization  
matplotlib==3.8.4  
seaborn==0.13.2  
## Machine Learning and preprocessing  
scikit-learn==1.4.2  
## Jupyter Notebook support  
jupyter==1.0.0  
pip install pandas numpy matplotlib seaborn scikit-learn  


# ▶️ How to Run
1. Clone the repo:
 ```bash
  git clone https://github.com/SourabhLahoti15/diabetes-detection.git
  cd diabetes-detection
```
2. Launch the notebook:
   ``` bash
   jupyter notebook DiabetesDetection.ipynb


# 🎯 Project Overview  
## Dataset:  
Source: Kaggle — Comprehensive Diabetes Clinical Dataset  
link: https://www.kaggle.com/datasets/priyamchoksi/100000-diabetes-clinical-dataset  
Rows: 100000  
Features: 'year', 'gender', 'age', 'location', 'race:AfricanAmerican',
       'race:Asian', 'race:Caucasian', 'race:Hispanic', 'race:Other',
       'hypertension', 'heart_disease', 'smoking_history', 'bmi',
       'hbA1c_level', 'blood_glucose_level', 'diabetes'
       
# Story telling and findings from power bi  
In the dataset, blood glucose levels (glucose) showed a strong positive correlation with diabetes occurrence, making it the most significant predictor. Patients with high BMI and higher age also had a greater likelihood of diabetes, highlighting obesity and aging as key risk factors. Interestingly, most diabetic patients fell in the 30–50 age group, with a concentration of cases observed among females. The data also revealed that a majority of diabetic patients had zero insulin value recorded, pointing to either missing data or abnormal insulin regulation. Overall, these visuals suggest that targeting weight management and regular glucose monitoring—especially among middle-aged individuals—could be vital in diabetes prevention.  
