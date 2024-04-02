Model Objective:-

The model aims to predict the price for Samsung mobile phones that belong to the range 0,1,2, & 3. The procedure has been performed using a supervised learning algorithm.

Organisation name:- Samsung

Product Division:- Smart Phones

Database Description:-

Price Range: 0,1,2 & 3 

Data source: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

Algorithms Applied: 

    1) K Nearest Neighbor (KNN) Algorithm
    
    2) Random Forest Regressor Algorithm
    
Important Libraries:

    1) Pandas
    
    2) Seaborn
    
    3) Matplot library
    
    4) Numpy
    
    5) Sk learn
    
Process:-

The model follows 5 steps:

    1) Database Aqcuistion: 
       After the data was extracted from Kaggle in a CSV format, it was uploaded to Jupyter Notebook using the Pandas library.

    2) Data Normalisation:
       It focuses on setting up independent variables that is factors other than the mobile prices at an equal scale during the application of KNN algorithm with the help of standard scaler technique to make sure that the values with larger magnitude do not dominate the distance.

    3) Training and testing:

       - 30% of the database has been assigned to testing procedure.
       - 70% of the dataset has been assigned to training procedure.

    4) Application: We will train the KNN model using K value as 1 to observe the prediction accuracy.

    5) Model Evaluation: 
    
        - Preparation of classification report to analyse the number of true cases of the model.
        
        - Visualisation of error rate with respect to the K neigborhood values to further enhance the model performance.
        
        - Assinging suitable K neighborhood value with the least error rate to maximise the model accuracy.

        - Impact: After the application of K values, the model has aquired the accuracy rate of 64%.  

    6) Random Forest Regressor algorithm: 
    
        - Application of Random Forest Regressor classifier to reduce the overfitting of the model and further increase the prediction accuracy.

        - Impact: After the application of Radnom Forest Regressor, the model has aquired an increase in the accuracy rate by 20% of up to 84%. 
        
    7) Data Visualisation: Application of Seaborn module to observe the predicted prices with actual current prices for the smart phones that belong to the price ranges of 0,1,2,3 & 4.


Conclusion:-

    - The price for the mobile phone belonging to the price range of 0,1 and 3 is expected to be increased.
    
    - The price for the mobile phone belonging to the price range of 2 is expected to be decreased.
    
    - The model is ready to be deployed for prediction procedure with the capability of 84% accuracy.
              
