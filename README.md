# Credit Card Fraud Detection Analysis
In this project Naive bayes classification is used for supervised machine learning algorithm,in which 492 frauds are analysed out of 2,84,807 transactions.
Basic Principle of Naive Bayes Algorithm -
The Bayes theorem is a mathematical formula for calculating conditional probability in probability and statistics.
Formula of Naive Bayes Theorem -
P(A/B) = (P(B/A) P(A))/P(B) 
if the output is 1, means the transaction is fraudaulent.
If the output is 0, means the transaction is genuine without any fraud.
Methods which we used in this project -
1. Training
2. Testing
3. Analysis
A learned Naive Bayes model stores a list of Probabilities.
1. probability for each Class in the Training Dataset: Class Probability
2. The Conditional prob. for each input values given class value: conditional Probability
so Class Probability of Fraudulent = 492/284,807
Class Probability for Non Fraudulent = 1 - (492/284,807)
Libraries Used in this Project are -
   1. Numpy 
   2. Pandas 
   3. Seaborn
   4. Matplotlib
   5. SK learn metrics

 Conclusion - 0.2% Fraud Transaction
              99.8% Genuine or Normal Transaction

Largest Score -
recall score:  0.8775510204081632
precision score:  0.08634538152610442
f1 score:  0.15722120658135283
accuracy score:  0.9838137705838981
ROC AUC: 0.9611556179872063 
Case-NB-4 gives me better model sensitivity (or recall) and precision as compared to Case-NB-1. So dropping some of redundant feature will ofcourse helps to make calculations fast and gain senstivity.
