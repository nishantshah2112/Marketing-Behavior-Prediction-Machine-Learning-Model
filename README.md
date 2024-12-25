# Marketing Behavior Prediction: Machine Learning Model

This project builds a machine learning model to predict user purchase likelihood based on engagement metrics and user behavior. The dataset simulates marketing interaction data for 500 users with features such as likes, shares, comments, and time spent on the platform.

---

### **Project Overview**
1. **Data Preprocessing**:
   - Cleaned missing values and encoded categorical variables.
   - Scaled numerical features using StandardScaler for better model performance.

2. **Modeling**:
   - Trained a **Random Forest Classifier** to predict the binary target variable (`Purchase_Likelihood`).
   - Evaluated the model using accuracy, precision, recall, F1-score, and AUC-ROC metrics.

3. **Key Outputs**:
   - **Feature Importance**: Identified the top features influencing purchase decisions.
   - **Confusion Matrix**: Visualized classification performance.
   - Predictions and the trained model were exported for further analysis.

4. **Business Implications**:
   - Insights to focus marketing campaigns on high-potential buyers.
   - Optimization strategies based on user engagement.

---

### **Technologies Used**
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Model**: Random Forest Classifier

---

### **Future Improvements**
- Perform hyperparameter tuning for enhanced performance.
- Experiment with additional models like XGBoost or Neural Networks.
- Integrate a dashboard for real-time predictions. 

For further details, explore the code and documentation in the repository.
