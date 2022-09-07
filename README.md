# Capstone-ML-Project
1.	Introduction 

This report will explain some of the significant points that done for the machine learning capstone project by the limitless group. It will be highlight the business problem, visualization part, which approaches or models were selected, the results, and what was done to improve the models in detail. 
2.	The Data

For the machine learning project, the selected dataset was related to the used cars in Saudi Arabia; It contains around 8248 rows and 13 columns; 
	Make: Name of the car company
	Model: Name of a car product
	Year: Year of Manufacturing
	Origin: Country of importer (Gulf / Saudi / Other)
	Color: Color of the used car
	Options: Full Options / Semi-Full / Standard
	Engine Size: The engine size of used car
	Fuel Model: Fuel Model size of used car (Diesel / Gas / Hybrid)
	Gear Type: Automatic / Manual
	Mileage: The average distance that a vehicle can travel on (in km)
	Region: The region in which the used car was offered for sale
	Price: Price of the used car (in SAR)
	Negotiable: If True, the price is 0. This means the price is negotiable (not set)

3.	The Project Objectives

The main objectives of the projects are:
	Building a regression model to predict the price of the used cars in Saudi Arabia.
	Building a classification model to predict the options of the used cars in Saudi Arabia.
	Understanding which variables are significant in predicting the price and options.
	Comparing different ML models, and finding the best one among them.

4.	The Business Problem

This project will be help the used car dealership owners, as they will be able to determine the appropriate price of the used cars based on the car model, year, color, options, engine size, gear type, mileage, and region. In addition, using a ML model to determine the price will be help to prevent price gouging and will be improving the sales management process to be resulted with an acceptable profit. 

5.	Dataset Feature visualization 

In this project, we prepared many visualizations to clarify the data set and to be able to create models. This pair shows us the relationships between several variables in the used car dataset which are: price, mileage, engine size, and year. By creating this perception, we can see in the Figure1 that the price of used cars in 2020 is higher than in other years. Also, the engine size for used cars, which is 5.0, has the highest price. The relationship between mileage and price is also an inverse relationship, the higher the mileage, the lower the price for the used car.

6.	The Approach & Results

We used many approaches to implement our Machine Learning for the used cars dataset project. First, we start working on building regression models. We select the price to as a target make the prediction. So, the baseline of our model will be the price. After that, we need feature selection and the target that we need to predict the price of the used cars. We did three regression models. We used decision trees for the first regression model. For the second regression model, we used a random forest. Also, we did the third regression model by using XGBoost.These three regression models will be evaluated for the model election. The selection of the best model was done based on the high degree of accuracy of the model compared to other models. The best model is the XGBoost model and that's because it has a training accuracy equal to 98.0% and the test set accuracy is equal to 81.0%. So, after we know that XGBoost is the best model we build a pipeline for the best model. After finishing the regression sections, we start on the classification model to make predictions on Options attributes in the used cars dataset. In the option attribute we have three options (Full, and Semi Full, Standard) will be represented as (2, 1, 0) respectively. The baseline of our model is Options. We did three classifications to predict the options. The first one is a simple classification model and we got 51.0% for the training accuracy and 49.0% for the test set accuracy. The second classification model is the decision tree classifier. As a result, the training accuracy is equal to 55.0 %, and the test set accuracy is equal to 53.0%. The third classification model is random forest. We got from this model accuracy equal to 98.0% for the training and 59.0% for the test set. The fourth classification model is XGBoost with 84.0% for the training accuracy and 59.0% for the test set accuracy. After that, we did a model evaluation so we can select the best model. The selection of the best model was done based on the high degree of accuracy of the model compared to other models. The best classification model is XGBoost Classification because it has an accuracy score equal to 59.04%.  After that, we did a hyperparameter tunning for the best model. Finally, we did pipeline. 

In conclusion, we used three models for regression and four models for classification to select the best model. For the regression model there was enough data and features to make a very good model with high score but not over fitting the data and can be used properly in the used cars dataset to predict the price of the used cars in Saudi Arabia based on the giving features. For the classification model we had average score not a bad score yet not very accurate that due to the lake of the data needed for this model but if more data and features were provided this model can be improved and be more accurate in predicting the options for each car if it's missing. Finally, we did hyperparameter tunning. In conclusion, we used three models for each regression and classifications to select the best model. 
Using Machine Learning on used cars dataset can make a big impact in the used cars market as there is many models can be used beside the two models, we made to more predictions that will lead to more efficient process by having a future sight and more clear vision of the future market of used cars in Saudi Arabia.
[Capstone Reporting (1).docx](https://github.com/LameesAlotaibi/Capstone-Project/files/9508242/Capstone.Reporting.1.docx)

Links:
Dataset:
https://www.kaggle.com/datasets/turkibintalib/saudi-arabia-used-cars-dataset[Final Capstone Project.zip](https://github.com/mashaelZaid/Capstone-ML-Project/files/9521948/Final.Capstone.Project.zip)

power bi:
https://app.powerbi.com/links/uB4U1Bb891?ctid=ed6d8a7a-6069-48d8-8b16-4b119276afef&pbi_source=linkShare 
Gant chart:
https://app.clickup.com/36919424/v/g/136p40-163
