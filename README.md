# IPL_winning-Team-Prediction

This project aims to predict the winning team in IPL (Indian Premier League) matches using machine learning models. The prediction is based on various match-related features and utilizes three different algorithms: Random Forest, Support Vector Machine (SVM), and Logistic Regression. The models are trained on historical match data and their predictions are served through a web-based interface built with Streamlit.

![Screenshot 2024-09-04 180707](https://github.com/user-attachments/assets/2854606a-af57-4c7d-9651-d441e5751b02)

## Key Components ## 


**1. Data Preparation**

     -Data Cleaning: The dataset is cleaned and preprocessed to handle missing values, categorical variables, and other inconsistencies.

     -Feature Engineering: Features such as team performance, player statistics, and match conditions are engineered to enhance model performance.

     -One-Hot Encoding: Categorical variables (e.g., team names, match venues) are converted into numerical values using One-Hot Encoding for compatibility with 
                          machine learning algorithms.

**2. Machine Learning Models Used**

    -Random Forest

    -Support Vector Machine (SVM)

    -Logistic Regression


**3. Model Training and Evaluation**

      -Training: Each model is trained using historical match data.

      -Evaluation: Models are evaluated based on metrics such as accuracy, precision, recall, and F1-score to determine their performance.

**4. Web Application**
   
    -Streamlit: Used to create an interactive web application where users can input match details and get predictions.

    -Pickle: The trained models are saved using Pickle for easy loading and prediction within the Streamlit application.

##  How to Use ##

Install Dependencies:


pip install pandas numpy scikit-learn streamlit pickle

 - 1.Prepare the Data: Load and preprocess your IPL match data using the provided scripts.

 - 2.Train the Models: Train the Random Forest, SVM, and Logistic Regression models using the historical match data.

  - 3.Save the Models: Use Pickle to serialize the trained models to files.

  - 4.Run the Streamlit Application:


streamlit run app.py

    Interact with the Web Interface: Enter the match details and view the predicted winning team.

## Contributions ##

Contributions, issues, and feature requests are welcome. Feel free to check this project if you want to contribute.
    
