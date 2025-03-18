## Titanic Survival | EDA and Modeling

**Project Type**: Machine Learning | Classification  
**Tools Used**: Python, Pandas, Matplotlib, Seaborn, Scikit-Learn, XGBoost    
**Dataset**: Titanic: Machine Learning from Disaster [Kaggle](https://www.kaggle.com/competitions/titanic)

### **Objective**  
The objective of this project is to predict survival outcomes of passengers on the Titanic based on various features such as age, sex, class, and other demographics. This analysis aims to identify key factors influencing survival and build a predictive model for survival prediction.

### **Key Steps**
- **Exploratory Data Analysis (EDA)**:
    - Analyzed the dataset to uncover patterns, correlations, and distributions.
    - Visualized relationships between features (e.g., age, class, sex) and survival.
    - Handled missing data by imputing or dropping rows/columns, and investigated feature distributions.
- **Data Preprocessing & Feature Engineering**:
    - Converted categorical variables into numerical formats using encoding techniques.
    - Created new features such as family size, name length, and primary cabin and for better model performance.
    - Normalized and scaled relevant features.
- **Model Training & Evaluation**:
    - Trained multiple models, including LinearSVC and XGBClassifier.
    - Compared model performances to select the best-performing model.

### **Results**  
The best-performing model was found to be XGBClassifer, with an accuracy of .8324. Key features such as **sex**, **class**, and **age** were found to be strong predictors of survival, and the model demonstrated a solid ability to predict outcomes based on the dataset.

🔗 **View Interactive Notebook (nbviewer)**: [nbviewer Link](https://nbviewer.org/github/christopherFlynn/Titanic-Survival/blob/main/titanic-survival-eda-and-modeling.ipynb)
