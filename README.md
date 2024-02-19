# Sentiment-Analysis-for-Product-Reviews

## Table of Contents
1. Data Preparation
2. Exploratory Data Analysis
3. Data Preprocessing
4. Text Vectorization
5. Model Building
6. Model Evaluation

<hr/>

## Data Preparation
### Reading in Data </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/read.png">

### Dropping the ID columns </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/id drop.png">

## Exploratory Data Analysis
### Time plot showing correlation between review date and star ratings </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/time plot.png">

### Bar plot showing correlation between verified purchases and sentiments </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/bar plot.png">

### Scatterplot showing correlation between helpful votes and total votes </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/scatterplot.png">

## Data Preprocessing
### Dropping columns </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/other drop.png">

### Cleaning the review headline column </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/clean.png">

### Word Cloud Visualization

## Text Vectorization
### Vectorization using Tfidf Vectorizer </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/vec.png">

### Data Splitting </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/split.png">

## Model Building
### Accuracy Table
<table>
  <th>
    
  <td>Model</td>
    <td>Accuracy</td>
  </th>
  <tr>
    <td>1</td>
    <td>Logistic Regression</td>
    <td>0.8974325726141079</td>
  </tr>
    <tr>
    <td>2</td>
    <td>Decision Tree Classifier</td>
    <td>0.8892634854771784</td>
  </tr>
    <tr>
    <td>3</td>
    <td>Support Vector Classifier</td>
    <td>0.9026192946058091</td>
  </tr>
    <tr>
    <td>4</td>
    <td>Multinomial Naive Bayes</td>
    <td>0.8952282157676349</td>
  </tr>
</table>

## Model Evaluation
### Classification Report </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/class.png">

### ROC/AUC Curve </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/roc.png">

### Confusion Matrix </br>
<img alt="image" src="https://github.com/Nalito/Sentiment-Analysis-for-Product-Reviews/blob/main/exports/confm.png">
