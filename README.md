# Fake News Classification
## Objective

In this project, we are going to classify whether a given news is **reliable** or **unreliable** using the given data set

## Data

**Data Source :**   [https://www.kaggle.com/c/fake-news](https://www.kaggle.com/c/fake-news)<br>
*Train DataSet*
-   **id**: unique id for a news article
-   **title**: the title of a news article
-   **author**: author of the news article
-   **text**: the text of the article; could be incomplete
-   **label**: a label that marks the article as potentially unreliable

		-   1: unreliable
		-   0: reliable
*Test Dataset*
-   **id**: unique id for a news article
-   **title**: the title of a news article
-   **author**: author of the news article
-   **text**: the text of the article; could be incomplete


## Methods Used

-   Classifications
-   Logistic regression
-   Decision tree
-   KNeighbours
-   Linear Discriminant
##  Project Description
Given a **title,  author and text** determine whether the news is reliable or unreliable (0 for unreliable and 1 for reliable).
<br>
 *With the help of given attributes we are going to combine all of the three important attributes i.e **title, author and text** into a single column so as to preserve all the important data and to make our data cleaning and preprocessing task much easier*  
 


## Quick Go Through Our Project

 1. Merged all three attributes _**title, author and text**_ into one new column **total**
 2. Filled Null Values
 3. Removed duplicate entries
 4. **Text Cleaning -**  Removed Url, special characters, stopwords, and performed Snow Ball Steaming.
 5. Cleaned both test and train data
 6. Used **Tf-Idf** to convert text into vector and also used **bigram**
 7.  Used different Machine Learning Models to find the one with the best accuracy
 8. Finally used Logistic Regression to predict our **test data**
 9. Saved the output in a **CSV** file
 10. Submitted on Kaggle with **accuracy of 97%**   

##  Conclusion
No model can be perfect, so with a score of 97 % accuracy, I am pretty much surprised. But we also use some more turning to see if we can further increase our model accuracy.


[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/CreatorGhost/FakeNewsClassification/blob/master/FakeNewsClassification.ipynb)
