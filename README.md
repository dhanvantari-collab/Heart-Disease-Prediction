# Heart-Disease-Prediction
Machine Learning project for predicting heart disease using Python.



❤️ Heart Disease Prediction Using Machine Learning

📌 Project Overview

This project predicts whether a person may have heart disease using medical data and Machine Learning. It uses the Logistic Regression algorithm to classify a person as having heart disease or not based on input health parameters.

🎯 Objectives

- Analyze heart disease data.
- Preprocess and explore the dataset.
- Train a Logistic Regression model.
- Evaluate model performance using accuracy.
- Build a predictive system for individual input data.

🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

📂 Project Structure

Heart-Disease-Prediction/

├── /content/Heart_Disease_Prediction.ipynb

├── /content/heart_disease_data.csv

└── README.md

📊 Dataset

The project uses a CSV dataset named "/content/heart_disease_data.csv".

The dataset contains medical features used to predict heart disease. The "target" column is the output variable:

- "1" – Heart disease
- "0" – No heart disease

Note: Ensure that "/content/heart_disease_data.csv" is available in the correct location before running the notebook.

⚙️ Methodology

1. Importing Dependencies

NumPy, Pandas, and Scikit-learn libraries are imported for data processing and machine learning.

2. Data Collection and Processing

- Load the CSV dataset.
- Explore the first and last rows.
- Check dataset dimensions and information.
- Check for missing values.
- Analyze statistical measures and target distribution.

3. Feature and Target Separation

- Features (X): All input columns except "target".
- Target (Y): The "target" column.

4. Train-Test Split

The dataset is divided into:

- 80% training data
- 20% testing data

Stratified sampling is used to maintain the target-class distribution.

5. Model Training

A Logistic Regression model is trained using the training dataset.

6. Model Evaluation

The model's accuracy is calculated on both training and testing data using Scikit-learn's "accuracy_score".

7. Predictive System

The trained model receives a set of medical feature values and predicts the corresponding class.

🚀 Installation and Execution

Step 1: Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL
cd Heart-Disease-Prediction

Step 2: Install Dependencies

pip install numpy pandas scikit-learn jupyter

Step 3: Add the Dataset

Place "/content/heart_disease_data.csv" in the project folder.

Step 4: Run the Notebook

jupyter notebook /content/Heart_Disease_Prediction.ipynb

Alternatively, upload the notebook and dataset to Google Colab and run the cells in order.

📈 Results

The notebook evaluates the model using training accuracy and testing accuracy. Run all cells to obtain the actual accuracy values.

🔮 Future Enhancements

- Compare Logistic Regression with other classification algorithms.
- Add confusion matrix, precision, recall, and F1-score.
- Improve data preprocessing and model validation.
- Develop a user-friendly web application.
- Improve prediction reporting and visualization.

⚠️ Disclaimer

This project is for educational and research purposes only. Its predictions are not a medical diagnosis and should not be used as a substitute for professional medical advice.

👨‍💻 Author

Miss. Dhanvantari S. Pingale 

📄 License

This project can be shared for educational purposes. Add a suitable open-source license if you intend to distribute it publicly.
