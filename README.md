# Banking Fraud Detection AI – An Agile Solution :
Access the web interface: http://127.0.0.1:5000/

<img width="1909" height="955" alt="image" src="https://github.com/user-attachments/assets/3f672531-8572-4d97-b240-09d0ea06fc9f" />


## Project Objective
Develop an automatic fraud detection system for banking transactions, combining machine learning techniques, dimensionality reduction, and resampling in order to optimize accuracy on a highly imbalanced dataset.  

<img width="1903" height="902" alt="image" src="https://github.com/user-attachments/assets/2c4690a1-07e6-406d-9879-4d073dd39007" />


## Technologies Used
- Python  
- Scikit-learn  
- Pandas, NumPy  
- SMOTE & Random Undersampling  
- PCA (Principal Component Analysis)  
- Flask (REST API)  
- Streamlit (Web Interface)  
- Google Colab & VS Code  

## Approach and Key Steps
1. **Data Exploration**: dataset analysis, visualization of class imbalance, and initial cleaning.  
2. **Preprocessing**: normalization, transformation of the time variable, and encoding if required.  
3. **Dimensionality Reduction**: applying PCA to improve visualization and reduce complexity.  
4. **Imbalance Handling**: combining SMOTE to oversample fraud cases with undersampling of normal transactions.  
5. **Modeling**: testing several models (Logistic Regression, Decision Tree, Random Forest) and selecting the best one based on Recall and Precision.  
6. **Deployment**: creating a REST API with Flask and an intuitive web interface with Streamlit to test live transactions.  

## Results
The final model achieves a strong balance between fraud detection (Recall) and limiting false positives (Precision), thanks to class balancing and careful feature selection. It is ready for production deployment through its integration with Flask and Streamlit.  

## Quick Start
```bash
# Run the Flask API
python app.py
