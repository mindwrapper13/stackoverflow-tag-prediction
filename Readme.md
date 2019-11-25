# StackOverflow Tag Prediction

## Abstract
This project presents a system that automatically assigns tags to questions from StackOverflow. The model performance was evaluated using Hamming Loss and Jaccard’s Score. The best-performing model was saved for predicting tags.

## Introduction
StackOverflow allows users to assign tags to questions to make them easier to find. Tags also help experts subscribe to specific topics, ensuring questions are addressed by the right people. This project develops a predictor that assigns tags based on the content of a question, considering the title and body of the question.

## Literature Review
Previous research on StackOverflow data has employed machine learning and analytics to explore various aspects such as user behavior, question quality, and contribution patterns. Researchers have used techniques like topic modeling and statistical analysis to categorize questions and assess their complexity. Tag prediction has also been studied using Bayesian probabilistic models and clustering approaches.

## Dataset Description
The dataset used is from the Kaggle competition on automatic tagging of StackOverflow posts. It contains over 6 million questions, including titles, HTML-marked question bodies, and corresponding tags. Due to computational limitations, we focused on a subset of the data, using the 1000 most frequent tags and sampling around 530,000 documents for training and evaluation.

## Results
We explored binary classification using Support Vector Machines (SVM). The hyperplane created by SVM separates data points with maximum margin. We evaluated SVM and found that the decision boundary effectively classified the data, providing promising results using Support Vector Classifier (SVC).

## Conclusion and Outlook
In this project, we built a basic classifier that predicts tags for StackOverflow questions based on the question title and body. Future work should focus on optimizing runtime and exploring additional features like tag co-occurrence, which may further improve model performance.

## References
- [Applied AI Course](https://www.appliedaicourse.com/)
- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/default.asp)
- [Precision and Recall Explanation](https://medium.com/@klintcho/explaining-precision-and-recall-c770eb9c69e9)
- [YouTube: Precision and Recall](https://www.youtube.com/watch?v=HBi-P5j0Kec)
- [StackOverflow Sparse Matrix Elements](https://stackoverflow.com/questions/15115765/how-to-access-sparse-matrix-elements)
- [SQLite Tutorial: Create Tables](http://www.sqlitetutorial.net/sqlite-python/create-tables/)
- [SQLite Tutorial: Delete](http://www.sqlitetutorial.net/sqlite-delete/)
- [StackOverflow: Select Random Row](https://stackoverflow.com/questions/2279706/select-random-row-from-a-sqlite-table)
