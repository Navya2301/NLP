# DATA SCIENCE NLP PASSWORD STRENGTH PROJECT

## Overview
This project predicts the strength of a password (Weak, Medium, Strong) using NLP and machine learning. By analyzing various features like length, frequency of lowercase, uppercase, digits, and special characters, we classify passwords effectively.

### Project Features
1. Data Loading and Cleaning:
   * Loaded the dataset from an SQLite database using pandas.
Removed unnecessary columns and handled duplicate and null values.
2. Feature Engineering:
   * Generated new features such as password_length, frequency of lowercase, uppercase, digits, and special characters.
Analyzed the distribution of these features across different password strengths.
3. Data Visualization:
   * Created box plots to visualize the relationship between the generated features and password strength.
Used violin plots and distribution plots to further analyze the distribution of features across different password strengths.
4. Model Training:
   * Applied TF-IDF vectorization to convert passwords into numerical feature vectors.
Trained a logistic regression model using these vectors to predict the strength of the passwords.
Split the data into training and testing sets to evaluate the model's performance.
5. Prediction:
   * Developed a function that allows users to input a password and receive a prediction of its strength (Weak, Medium, or Strong).

### Installation
1. clone this repository
   
   ```
   git clone https://github.com/Navya2301/NLP.git
   cd NLP
   ```
2. Install dependencies
   ```
   pip install -r requirements.txt
   ```
3. Ensure You Have the Database File:
      * Place the password_data.sqlite file in the root directory of the project.

