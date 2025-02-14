# SONAR - Rock vs Mine Prediction  
Welcome to the SONAR - Rock vs Mine Prediction project repository! This project aims to classify SONAR signals into rocks or mines using machine learning techniques. The dataset used for this project contains 60 attributes representing the energy of sound signals bounced off from underwater objects. Each instance in the dataset is labeled as either ‘R’ (rock) or ‘M’ (mine).

## Table of Contents  
1. Features  
2. Installation  
3. Usage  
4. Dataset  
5. Data Preprocessing  
6. Models and Algorithms  
7. Results  
8. License  

## Features  
- Classification of SONAR signals into rocks or mines.  
- Data preprocessing and feature scaling.  
- Exploratory data analysis to understand the dataset.  
- Model training using Random Forest classifier.  
- Evaluation using various metrics.  

## Installation  
### To run this project, ensure you have the following dependencies installed :    
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib (Optional, for visualization)  
### You can install them using pip:  
pip install numpy pandas scikit-learn matplotlib  

### Clone the repository:  
- git clone https://github.com/DarshiniMahesh/SONAR-Rock-vs-Mine-Prediction.git  
- cd SONAR-Rock-vs-Mine-Prediction  

## Usage  
Run the main script to train the model and make predictions:  
python main.py  

## Dataset  
The dataset used for this project is the SONAR dataset, which contains 60 attributes representing the energy of sound signals bounced off from underwater objects.   Each instance is labeled as either ‘R’ (rock) or ‘M’ (mine).  

## Data Preprocessing  
Detailed steps for data preprocessing, including handling missing values, scaling features, and splitting the dataset into training and testing sets.  

- ### Exploratory Data Analysis  
  Visualization and analysis of the dataset to gain insights and understand the distribution of data.  

## Models and Algorithms  
The model is trained using a Random Forest classifier from the Scikit-learn library.   The dataset is split into training and testing sets.   The classifier is then trained on the training set and evaluated on the testing set.  

- ### Evaluation Metrics  
  Description of the metrics used to evaluate the model, such as accuracy, precision, recall, and F1-score.  

## Results  
The model achieved an accuracy of 85% on the test dataset. Detailed results and analysis, including confusion matrix and classification report.  

## License  
This project is licensed under the MIT License.  
