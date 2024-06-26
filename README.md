# BMI_prediction_using_ML
Our team of five innovators created a groundbreaking project: predicting Body Mass Index (BMI) using the Random Forest algorithm, a key tool in machine learning. This collaboration produced a sophisticated system for accurate BMI assessment, showcasing our commitment to healthcare innovation.


---

# Body Mass Index Prediction using Random Forest Algorithm

This project focuses on predicting Body Mass Index (BMI) using the Random Forest algorithm, a popular machine learning technique. The aim is to create a robust model that accurately categorizes individuals based on their BMI into different health categories.

# Files Used

`500_Person_Gender_Height_Weight_Index.csv`: This CSV file contains the dataset used for training and testing the model. It includes information such as gender, height, weight, and BMI index of 500 individuals.

- **`bmi_classifier.ipynb`:** This Jupyter Notebook serves as the main script for the project. It contains the Python code for data preprocessing, model training, evaluation, and visualization.

- **`README.md`:** This markdown file provides an overview of the project, its purpose, and instructions for running the code.

### Libraries Used

- **NumPy:** Used for numerical computing and handling arrays and matrices efficiently.

- **Pandas:** Utilized for data manipulation and analysis, particularly for reading and processing the dataset.

- **Seaborn and Matplotlib:** Employed for data visualization to gain insights into the dataset and model performance.

- **Scikit-learn (sklearn):** A machine learning library used for model building, including preprocessing, model selection, and evaluation.

- **Tkinter:** A GUI library in Python used to create a simple interface for users to input their data and get BMI predictions.

### How It Works

1. **Data Preprocessing:** The dataset is loaded using Pandas, and initial exploration is performed to understand its structure. Data preprocessing steps include handling categorical variables, scaling numerical features, and splitting the data into training and testing sets.

2. **Model Training:** The Random Forest algorithm is chosen for its ability to handle complex datasets and reduce overfitting. Hyperparameter tuning is performed using GridSearchCV to optimize the model's performance.

3. **Model Evaluation:** The trained model is evaluated using classification metrics such as accuracy, confusion matrix, and classification report to assess its predictive capabilities.

4. **GUI Implementation:** A simple GUI is created using Tkinter to allow users to input their gender, height, and weight. Upon clicking the "Predict BMI" button, the model predicts the BMI index category, and the result is displayed to the user.

### Running the Project

To run the project locally, ensure you have Python installed along with the required libraries . You can execute the `bmi_classifier.ipynb` notebook in Jupyter or any compatible environment to explore the code and interact with the GUI.
