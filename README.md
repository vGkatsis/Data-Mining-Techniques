# Data Mining Techniques

### This project consists of two parts:

1. **Data Visualization**
2. **Sentiment Analysis**

### 1. Data Visualization

In this part data are taken from crime.csv and information is extracted out of them in the form of graphs and plots.
Techniques used include:

* Data grouping and plotting
* KMeans Clustering
* Data grouping and plotting on interactive map

### 2. Sentiment Analysis

In this part we use users twitts contained in twitter_data folder, in order to train and test sentiment analysis models. 

**Sentiment analysis refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information.**

This projects aims to categorize previously ungiven twitts as **Positive**, **Negative** or **Neutral**.

Steps followed in order for this goal to be achieved are:

1. Reading Data
2. Preprocessing
3. Stemming
4. Feature Creation using:
   * Bag Of Words
   * Tf-Idf
5. Classification using:
   * Linear SVM
   * KNN
  
 
### Requirements:
Both projects are written in jupiter notebook
* anaconda with python2.7
* gensim lib (conda install -c anaconda gensim)
* wordcloud lib (conda install -c conda-forge wordcloud)
* folium lib (conda install -c conda-forge folium)
* run the nltk.download() command and install all packages
