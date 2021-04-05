# Profiling Hate Speech Spreaders on Twitter
We tried out several machine learning approaches with different features in order to find the best solution for predicting whether the author of several tweets is a hate spreader. The Dataset of PAN @ CLEF 2021 shared Task which contain 200 authors with 200 tweets per author was used for this purpose. 

Five machine learning models including Logistic Regression, Random Forest, linear Support Vector Machine, Neural Network and K-Neighbours Classifier were used based on features from ‘word’-Tf-Idf Vectorizer, ‘char’-Tf-Idf vectorizer and Count Vectorizer. Comparisons between models and hyperparameters were done. 

The best model using features of Key phrase-based Method was Random Forest and it resulted in 0.69 F1 score and 0.70 accuracy; for ‘char’-Tf-Idf Method it was also Random Forest, giving almost 0.73 accuracy and 0.72 F1 score; ‘word’-Tf-Idf demonstrated the best result using Neural Network approach (0.75 accuracy and 0.75 F1 score) although other models within ‘word’-Tf-Idf showed rather poor results (< 0.7). 
