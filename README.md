# 🔋 EV Battery Quality Classification & Predictive Modeling
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 📌 Project Description
This project conducts a comparative analysis between Deep Learning (Keras/TensorFlow) and Random Forest (Scikit-learn) techniques to classify electric vehicle (EV) battery quality based on manufacturing data. The goal is to support automated quality control by accurately predicting battery conditions.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 📊 Dataset
The dataset contains 20,000 EV battery samples with critical manufacturing features, including:

	•	Temperature (Ambient)
	•	Capacity (mAh)
	•	Internal Resistance (mOhm)
	•	Electrolyte Volume (ml)
	•	Other process parameters
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 🎯 Objective
To develop and compare AI-based models to classify battery quality into three categories:

	•	Grade A
	•	Grade B
	•	Scrap
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 🛠 Tools

	•	Python
	•	TensorFlow / Keras
	•	Scikit-learn
	•	Pandas
	•	Matplotlib
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# ⚙️ Methods

	1.	Data preprocessing & Cleaning
	2.	Feature selection & Data Normalization
	3.	Deep Learning model development
	4.	Random Forest development
	5.	Model Comparison & Evaluation
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 🎯 Target Variable

	•	QC_Grade
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 💡 Key Findings

	•	Model Performance: The Random Forest model achieved superior performance with an Accuracy and F1-Score of 100% (1.0). The Deep Learning model also performed exceptionally well, achieving an Accuracy of 99.64% (0.996392).
	•	Feature Importance: Analysis using the Random Forest model identified Anode_Overhang_mm as the most critical factor in determining battery quality, with an importance score of approximately 75.2%. This was followed by 			
		Internal_Resistance_mOhm at 15.9%.
	•   Physical Insight: A proper Anode Overhang is a vital indicator of battery cell safety and structural integrity, as it prevents the formation of lithium dendrites that can cause internal short circuits. These AI findings enable 
		more precise and efficient Quality Control (QC) compared to traditional inspection methods.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 💻 Source Code

[View the full analysis in Jupyter Notebook](MINI_PROJECT_PHY_483.ipynb)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
# 👤 Author

PHY483 AI Project

:::
