# titanic

This project's aim is to predict whether a passenger survived the Titanic shipwreck or not. You will use both a Decision Tree Classifier and a Support Vector Machine to do this and compare the results. <br/>

The general steps are data exploration and analysis, data pre-processing and transformation (handling missing values, converting categorical features into numeric, converting discrete features into binary, etc.), and implementing your classifier. <br/>

The classic Titanic dataset provides information on the fate of passengers on the Titanic, summarised according to economic status (class), sex, age, and survival. <br/>

You will find two data files:<br/>
<li>Training set (titanic_train.csv) should be used to build your ML models.
<li>Test set (titanic_test.csv) should be used to see how well your model performs on unseen data.
  
<h4> Data Description and Notes:</h4>
Pclass: A proxy for Socio-Economic Status (SES).
<li>1st = Upper
<li>2nd = Middle
<li>3rd = Lower

Age: Age in years. It is fractional if less than 1. If the age is estimated, it is in the form of xx.5.

SibSp: The number of siblings/spouses aboard the Titanic. The dataset defines family relations in this way:
<li>Sibling = brother, sister, stepbrother, stepsister
<li>Spouse = husband, wife (mistresses and fiancés were ignored)

Parch: The number of parents/children aboard the Titanic. The dataset defines family relations in this way:
<li>Parent = mother, father
<li>Child = daughter, son, stepdaughter, stepson
<li>Some children travelled only with a nanny, therefore Parch = 0 for them.

Embarked: The port of embarkation, 
<li>C = Cherbourg, 
<li>Q = Queenstown, 
<li>S =Southampton. 

Ticket: The ticket number.

Fare: The passenger fare.

Cabin: The cabin number.
