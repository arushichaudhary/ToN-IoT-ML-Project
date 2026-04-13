ToN_IoT Machine Learning Project

Overview
This project implements a complete machine learning pipeline on the ToN_IoT dataset to classify network traffic into normal and attack categories.

Team Members
- Member 1: Data Preprocessing
- Member 2: Data Cleaning
- Member 3: Encoding
- Member 4: Feature Scaling
- Member 5: Model Training
- Member 6: Evaluation & Visualization

Dataset
We used a subset of the ToN_IoT dataset (Network data).
Due to large size, only a sample of the dataset is included.

Steps Performed
1. Data Preprocessing
- Loaded dataset
- Checked structure ("head", "shape", "info")
- Handled missing values
- Converted categorical data into numeric format

2. Data Cleaning
- Removed duplicates
- Dropped irrelevant columns

3. Encoding
- Converted categorical features using Label Encoding / One-Hot Encoding

4. Feature Scaling
- Applied StandardScaler to normalize features

5. Model Training
- Used Random Forest Classifier
- Split data into training and testing sets

6. Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

Results
- Achieved approximately 93–95% accuracy on the dataset sample
- Model effectively distinguishes between normal and attack traffic

Visualization
- Bar plot of class distribution
- Confusion matrix heatmap

How to Run
1. Open the notebook in Google Colab
2. Upload dataset file
3. Run all cells step-by-step

Conclusion
This project demonstrates how machine learning can be used for intrusion detection by analyzing network traffic data.

Team Members (Group-8)
1. PARI SANGAMNERKAR (23BCE11057)
2. AARUSHI CHAUDHARY (23BCE11152)
3. HIYA DULLU (23BCE11063)
4. SANJITH MOOS (23BCE11149)
5. PIYUSH SANGMESHWAR KANDURKE (23BCE11058)
6. ADVAIT SAHU (23BCE11069)
