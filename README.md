# **Crop Recommendation Model**

## **Overview**

The Crop Recommendation Model is a machine learning-based solution designed to assist farmers and agricultural stakeholders in selecting the most suitable crop for cultivation based on environmental and soil conditions. By leveraging data-driven insights, this model aims to enhance crop productivity and optimize resource utilization.

## **Features**

Input Parameters: Accepts soil and environmental parameters such as nitrogen (N), phosphorus (P), potassium (K) levels, temperature, humidity, pH, and rainfall.

Output: Recommends the most suitable crop for the provided conditions.

Machine Learning Techniques: Uses state-of-the-art algorithms for accurate predictions.

User-Friendly: Can be integrated into web or mobile applications for ease of use.

## **Dataset:**

The model is trained on a dataset containing:

Soil parameters: N, P, K levels.

Environmental conditions: Temperature, humidity, rainfall, and pH levels.

Target variable: Recommended crop.

Ensure you have the dataset in the required format before running the model. The dataset used for this model can be found here.

## **Installation**

Clone this repository:

git clone https://github.com/AFK-Kuntal/Crop_Recommendation_Model.git
cd Crop_Recommendation_Model
(optional) you can just simply download and unzip

Install required dependencies:
```bash
pip install -r requirements.txt
```
Ensure the dataset is in the /data directory.

Now open terminal and type this command:-
```bash
streamlit run app.py
```


## **Model Training**

The model is built and trained using the following steps:

Data Preprocessing: Handles missing values, scaling, and feature encoding.

Feature Selection: Selects the most relevant features for the task.

Model Building: Utilizes algorithms such as Random Forest, Decision Tree, or Logistic Regression.

Evaluation: Assesses the model's accuracy, precision, recall, and F1 score using test data.

## **Results**

The model achieves the following metrics:

Accuracy: 99.4%


### Libraries: Scikit-learn, Pandas, NumPy, Matplotlib

