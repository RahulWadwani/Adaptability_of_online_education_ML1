# Adaptibility_of_online_education_ML1
Machine Learning project 
<hr>
<h1>1. Data Exploration</h1>
<ul>
  <li>Shape of the Dataset           - (1205 rows and 14 columns)</li>
  <li>5 Sample points of the Dataset - randomly getting 5 datapoints</li>
  <li>Type of the column             - all categorical column </li>
  <li>Check for null values          - contains no null values.</li>
  <li>Describing the function        - Mathematically details about each column</li>
  <li>Duplicate dataset              - contains duplicate values</li>
</ul>
<h2> Insights After Data Exploration </h2>
<p>contains 1205 rows or data points. The dataset contains 14 columns and all the columns are categorical data. It contained almost 949 duplicate values removing these rows would result in small data of 250 approx which is not good. The good thing about this data is that it contains no null values </p>
<h1>2. Visualization </h1>
<ul>
  <li>Univariate Analysis   - plotting a graph of 1 column at a time using pandas</li>
  <li>Bivariate Analysis    - plotting a graph of 2 columns using count plot </li>
  <li>Multivariate Analysis - plotting a graph of 3 columns using countplot</li>
</ul>
<h2> Insights After Visualization </h2>
<p>financial, class duration and device columns are right-skewed, and the age column is not evenly distributed rest in univariate analysis
whereas in bivariate analyses ages below 15 years go to non-government schools age belonging to range 21-25 was an IT student. mostly all the group students belonged to the middle-class, age group between 6-10,16-20,26-30 had low adaptability on online education, Rich people had more adaptability than middle class or poor-class people, Being an IT Student does not have any effect on adaptability. Adaptabilty becomes very low when load_shedding is low and has a location </p>
