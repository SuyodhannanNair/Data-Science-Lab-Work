WATER QUALITY ANALYSIS: PREDICTING WATER POLLUTION

Description of the project:
This project's goal is to provide an assessment of the quality of water and to consistently be able to classify the water as potable (safe for consumption) or non-potable. To perform this classification, a set of methods employing Machine Learning will be used. The types of data that will be collected to accomplish this include: analysis of physicochemical parameters (e.g., pH, hardness, turbidity, etc.), chemical concentration levels, and any other variables necessary to provide a full and detailed assessment of the quality of the water.
 
Dataset Source: Kaggle – Water Potability
Dataset: water_potability.csv
Link: https://www.kaggle.com/datasets/adityakadiwal/water-potability

Description of dataset:
The dataset contains water quality measurements with the following features:
  - pH
  - Hardness
  - Solids (Total Dissolved Solids)
  - Chloramines
  - Sulfate
  - Conductivity
  - Organic Carbon
  - Trihalomethanes
  - Turbidity
  - Target: Potability (0 = Not Safe, 1 = Safe)

Steps Performed:
1. Data Cleaning
   - Handled missing values using mean imputation
   - Ensured dataset consistency

2. Exploratory Data Analysis
   - Checked data distribution and imbalance
   - Observed relationships between features and target

3. Visualization
   - (Optional) Correlation analysis and feature relationships
   - Identified important influencing parameters

4. Model Building
   - Split dataset into training and testing sets
   - Applied feature scaling using StandardScaler
   - Trained models:
     - Decision Tree Classifier
     - Random Forest Classifier
   - Evaluated models using classification metrics

Results:
- Random Forest performed better than Decision Tree
- Sample Metrics:
  - Accuracy: ~0.68
  - Precision: ~0.64
  - Recall: ~0.60
  - F1 Score: ~0.62

- Key Findings:
  - Water quality prediction is sensitive to dataset quality
  - Machine learning models may not fully align with real-world potable standards
  - Combining ML with domain-based rules improves reliability

Tools Used:
- Python
Python Libraries: - NumPy
                  - Pandas
                  - Scikit-learn

Conclusion:
This project provides an example of machine learning applied to the assessment of water quality through environmental monitoring. Although the predictive performance of the model is generally adequate, applying domain knowledge (i.e., the safe ranges of parameters) will improve the performance of the model in the real world. Therefore, we recommend a hybrid approach to practical applications of machine learning and rule-based validation.

Author: Suyodhannan. S. Nair
Golden Gate University Worldwide
Summer-C Batch, Computing
