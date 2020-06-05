# Fake News Classification
## Objective

In this project, we are going to classify whether a given news is **reliable** or **unreliable** using the given data set

## Data

**Data Source : **  [https://www.kaggle.com/c/fake-news](https://www.kaggle.com/c/fake-news)
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

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.
### Methods Used

-   Classifications
-   Logistic regression
-   Decisiontree
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
 4. **Text Cleaning - ** Removed Url, special characters, stopwords, and performed Snow Ball Steaming.
 5. Cleaned both test and train data
 6. Used **Tf-Idf** to convert text into vector and also used **bigram**
 7.  Used different Machine Learning Models to find the one with the best accuracy
 8. Finally used Logistic Regression to predict our **test data**
 9. Saved the output in a **csv** file
 10. Submitted on Kaggle with **accuracy of 97%**   

