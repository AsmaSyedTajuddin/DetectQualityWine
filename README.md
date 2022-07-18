# DetectQualityWine
Determining Red Vine Quality using Machine Learning

![1*pZf4I6Ft2EHsfPjCJOtZ6A](https://user-images.githubusercontent.com/100385953/179432506-e166710e-7422-4154-9543-31389360c6b3.jpeg)

Photo: Medium

“Can quality of wine be determined without using wine testing techniques, in other words, can we used predictive technique of machine learning to quantify the wine quality with scale and lesser expertise?”
The question whether statistical techniques can be used to determine the quality of wine without the need for individual inspection of wine tester will be carry out in this article.
DATA
This dataset is common in Kaggle open sources however, you might actually find articles in medium that used the cool and advance machine learning algorithm for solving this problem like Random Forest, Neural network and Support Vector machine and telling you what is the accuracy, precision, recall and f-1 score of the model without actually doing the proper knowledge acquisition of where quality of wine derived from. Of course, the power of machine learning do not require the one who implement it to actually know the input and give a great result. But it sure will help the machine learns better if the one who supervised the machine understand what are the relationships of inputs to output.

In this project we will be using Machine Learning to determine the quality of Red Wine with the help of factors like the chemical composition of the vine the contenct of sulpher, alchohol and the quality of the wine.

Time Line for the Project:

Importing libraries
Data Analysis
Data Preprocessing
Prediction using KNN
Classification using SVM


Fixed acidity: The non-volatile acid found in wine whihc are tartaric, malic, citric, and succinic. All of these acids originate in grapes with the exception of succinic acid, which is produced by yeast during the fermentation process.
Volatile acidity: the acidic elements of a wine that are gaseous, rather than liquid, and therefore can be sensed as a smell, showing an aroma, rather than found on the palate.
citric acid: a weak organic acid, which is often used as a natural preservative or additive to food or drink to add a sour taste and freshness to food.
residual sugar: the amount of sugar remaining after fermentation stops, it’s rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.
chlorides: the amount of salt in the wine
free sulfur dioxide(SO2): SO2 is used throughout all stages of the wine-making process to prevent oxidation and microbial growth. Excessive amounts of SO2 can inhibit fermentation and cause undesirable sensory effects.
total sulfur dioxide: amount of free and bound forms of S02S02; in low concentrations, SO2SO2 is mostly undetectable in wine, but at free SO2SO2 concentrations over 50 ppm, SO2SO2 becomes evident in the nose and taste of wine
density: the density of water is close to that of water depending on the percent alcohol and sugar content
pH: Winemakers use pH as a way to measure ripeness in relation to acidity. Low pH wines will taste tart and crisp, while higher pH wines are more susceptible to bacterial growth. Most wine pH’s fall around 3 or 4.
Sulphates: a wine additive which can contribute to sulfur dioxide gas (S02S02) levels, which acts as an antimicrobial and antioxidant.
alcohol: the percent alcohol content of the wine.
Now we have a rough understanding of our features, let’s look at the our dataset.
RED VS. WHITE
In the world of wine, the difference between red and white wine is not just its color, but the ingredient, the method of wine-making and aging. Because of these differences, the physio-chemicals will be different determinant when it comes to quantify the quality of wine.
