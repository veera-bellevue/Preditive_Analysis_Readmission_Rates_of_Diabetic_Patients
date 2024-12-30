# Preditive_Analysis_Readmission_Rates_of_Diabetic_Patients
Preditive_Analysis_Readmission_Rates_of_Diabetic_Patients
📋 Table of Contents

Overview
Dataset
Installation
Usage
Models
Results
Contributing
License

🎯 Overview
This project aims to predict and analyze hospital readmission rates for diabetic patients using machine learning techniques. By analyzing a comprehensive dataset from 130 US hospitals, we work to identify key factors influencing readmission rates and provide actionable insights for healthcare providers.
Key Objectives

Predict likelihood of patient readmission
Identify key factors influencing readmission rates
Provide actionable insights for reducing readmissions
Analyze demographic and treatment impact on outcomes

📊 Dataset
The analysis uses the "Diabetes 130-US Hospitals" dataset from UCI Machine Learning Repository.
Dataset Characteristics:

101,766 hospital records
50 features per record
Time span: 1999-2008
Coverage: 130 US hospitals

🚀 Installation
bashCopy# Clone the repository
git clone https://github.com/veera-bellevue/Preditive_Analysis_Readmission_Rates_of_Diabetic_Patients

# Navigate to the project directory
cd diabetes-readmission-prediction

# Install required packages
pip install -r requirements.txt
Dependencies
textCopynumpy>=1.19.2
pandas>=1.2.3
scikit-learn>=0.24.1
matplotlib>=3.3.4
seaborn>=0.11.1
plotly>=4.14.3
💻 Usage
pythonCopy# Example code for running the analysis
from src.models import train_model
from src.visualization import plot_results

# Train the model
model = train_model(data_path='data/processed/diabetes_data.csv')

# Generate visualizations
plot_results(model, save_path='results/figures/')
🤖 Models
The project implements three main models:
1. Logistic Regression

Baseline model
Binary classification
High interpretability

2. Random Forest Classifier

Handles nonlinear relationships
Feature importance ranking
Missing value handling

3. Support Vector Machine (SVM)

High-dimensional space handling
Kernel flexibility
Robust to overfitting

📈 Results
Current model performance metrics:
Will be updated soon
📊 Visualizations
Key visualizations include:

Age distribution analysis
Length of stay patterns
Demographic breakdowns
Feature correlation heatmaps

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request


🙏 Acknowledgments

UCI Machine Learning Repository for providing the dataset
Healthcare professionals who contributed to data collection
Bellevue University DSC 630 course staff

📞 Contact
Veera Indugu - https://www.linkedin.com/in/veera-venkata-raghun-indugu/
Project Link: https://github.com/veera-bellevue/Preditive_Analysis_Readmission_Rates_of_Diabetic_Patients
📚 References

UCI Machine Learning Repository - Diabetes Dataset
