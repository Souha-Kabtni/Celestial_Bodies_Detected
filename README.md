![image](https://github.com/Souha-Kabtni/Celestial_Bodies_Detection/assets/133057039/7d0e9e30-8584-4bb6-b65c-a803b34c48f3)


# Celestial_Bodies_Detection

Souha Kabtni

## Predicting Celestial Bodies According to their Spectral Properties

The categorization of stars, galaxies, and quasars based on their spectral properties is a crucial concept in astronomy. By dividing stars into different categories based on factors such as their temperature, luminosity, and chemical composition, we can gain insight into their physical properties and evolutionary stages.


Data on Celestial Objects from the Sloan Digital Sky Survey - Data Release 18. Click [here](https://docs.google.com/spreadsheets/d/1r0O_8CsKY4KMKlf2aHoOIxbXElmb_fVxeNreNhfS8ms/edit#gid=2032989002) to download the dataset.

For this dataset, there were ``` 100,000 rows```  and ``` 43 columns```.

## Data Dictionary

![image](https://github.com/Souha-Kabtni/Celestial_Bodies_Detection/assets/133057039/a24499b6-73c8-4804-968f-c3823eb9f85b)


## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis

    - A heatmap was visualized to display the relationships between feature/feature and feature/target. 
    - Distplots were visualized for each feature/target relationship. 
    - This gave a good baseline for univariate EDA.

### Explanatory Data Analysis

    - 1 line plot and one scatterpolar were chosen.
    - The Scatter polar was chosen to showcase the Top most Important Features to the Target. 
    - The line plot was chosen to show how the 'Redshift' feature helps differentiate between the 3 celestial objects. 

### Explanatory Visuals

![image](https://github.com/Souha-Kabtni/Celestial_Bodies_Detection/assets/133057039/8be7ede0-d659-4114-a919-c2572ec9a01c)

This scatter polar, clearly shows that redshift is the most important feature that helped us classify the data. So this is the best in terms of splitting ability. PetroR50_i, PetroR50_g, PetroR50_z, PetroR50_u,, and PetroR50_r are the following most important features that impact the distinguishing between all 3 celestial bodies. 

![image](https://github.com/Souha-Kabtni/Celestial_Bodies_Detection/assets/133057039/f7aee84c-39b4-426a-9ecc-97d1019d4268)

The line plot shows that QSO is by far the most distant celestial object for it is the most redshifted. Both GALAXY and STAR are not that distant from the Earth with close Redshift values.

## Pre-processing:

Having performed all data cleaning steps, my data set had to be scaled to avoid exploding weights. Besides, PCA was applied to reduce the feature space I am working with (I started with 42 features, and with PCA applied, I ended up with 23 features that helped capture 99% of the variance in the Target class variable. 

## Machine Learning Using the Following Models:

    - k-nearest neighbors (KNN) Algorithm
    - Random Forest Classifier Algorithm
    - Logistic Regression Algorithm
    - XGBoost Algorithm
    - Deep Learning using the Sequential model


## Models Evaluated & Results

+ k-nearest neighbors (KNN) Algorithm (Testing Set):
  
    + Accuracy score: ``` 0.97 ``` 
    + 
 
+ Random Forest Classifier Algorithm (Testing Set):

    + :```  0.98 ``` 
    + 

+ Logistic Regression Algorithm:

    + : ``` 0.99 ``` 
    + 

+ XGBoost Algorithm (Testing Set):

    + : ``` 0.99 ``` 
    + 

+ Deep Learning using the Sequential model (Testing Set):

    + : ``` 0.596 ``` 
    + 


The Final Model Chosen was ................... (talk about the number of layers, nodes, epochs used + any regularization technique used: Dropout, Early stopping, l1/l2, the time the model took to fit (to learn the connections))

1. classification_report

2. ConfusionMatrixDisplay.from_predictions

3. 

4.

Using this model to make sales predictions about food items sold at various stores would not be very reliable. A prediction error of  $1,055.975 (that represents almost 52.8% of the mean values of the Item-Outlet sales) cannot be overlooked.


## Recommendations



## Limitations & Next Steps



## For Further Information
For any additional questions, please contact:

Souha Kabtni
souha.kabtni.data@gmail.com

