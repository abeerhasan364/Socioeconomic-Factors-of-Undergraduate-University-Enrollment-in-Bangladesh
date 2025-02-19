# Socioeconomic-Factors-of-Undergraduate-University-Enrollment-in-Bangladesh 
 

This project analyzes **socio-economic factors influencing undergraduate university enrollment** in Bangladesh. Using **logistic regression and machine learning models**, it evaluates students' likelihood of enrolling in public or private universities based on various socio-economic attributes.  It contains 600 samples with 15 variables. 

---

## **Dataset**  
The dataset consists of **undergraduate admission survey data from Bangladesh**, covering factors such as:  
- **Household income**  
- **Parental education levels**  
- **Location (urban/rural)**  
- **SSC & HSC exam scores**  
- **University preference (public/private)**  

---

## **Objective**  
✔️ Identify key socio-economic factors affecting university enrollment  
✔️ Compare **logistic regression** with other machine learning models  
✔️ Evaluate **model performance** using accuracy, confusion matrix, and AUC  
✔️ Generate **insights** to inform education policy in Bangladesh  

---

## **Methodology**  
1. **Data Preprocessing**  
   - Handling missing values  
   - Feature selection  
   - Encoding categorical variables  

2. **Model Training & Evaluation**  
   - **Logistic Regression** (Primary Model)  
   - **Decision Tree, Random Forest, SVM, Neural Networks** (Comparison)  
   - Performance metrics: **Accuracy, AUC, Confusion Matrix**  

3. **Results & Interpretation**  
   - Feature importance analysis  
   - Policy recommendations based on findings  

---

## **Installation & Running the Notebook**  
To run this project locally, follow these steps:  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/university-admission-bd.git
cd university-admission-bd
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebook**  
```bash
jupyter notebook Undergrad_admission_bd.ipynb
```

---

## **Dependencies**  
Ensure you have the following Python libraries installed:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## **Project Structure**  
```
📂 university-admission-bd  
 ┣ 📜 Undergrad_admission_bd.ipynb  # Jupyter Notebook with analysis  
 ┣ 📜 README.md                      # Project documentation  
 ┣ 📜 requirements.txt                # List of dependencies  
```

---

## **Future Improvements**  
🔹 Include **more socio-economic variables** for deeper insights  
🔹 Apply **feature engineering** for better model accuracy  
🔹 Conduct **regional comparisons** for policy recommendations  

