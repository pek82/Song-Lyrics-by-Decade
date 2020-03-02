Grading Student Essays Project

Paul Kruger 


Project Goals

Can you predict a song’s decade only by its lyrics?

The Dataset

The Billboard Top 100 Pop Songs for each year from 1965-2015, including:  Artist, Rank, Year, All Lyrics

The Data Prep

Counting, lemmatizing, vectorizing each word in the dataset.  Removing stop words, dropping very infrequent words.  Grouping songs by decade

Models
Logistic Regression:  with One vs. Rest Classifier
Mulitnomial Naive Bayes
Decision Trees
Bagged Trees
Random Forest
Random Forest:  with GridSearch Parameter Tuning (BEST MODEL)

Final Conclusions

Best model (RF w/Grid Search):  
Accuracy = 47% vs. 20% baseline
High number of features results in low interpretabilty






