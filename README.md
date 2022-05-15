# KNIME-Lab-4

This week we've been working on the MNIST project which helped us obtain skills in working with categorical data. The aim of the project was to classify handwritten digits into categories given the handwritten images. The algorith was created on a train dataset and then used on a train set. This project also relied on the CRISP-DM framework for Machine Learning.

The main learning points included the calculation of accuracy framework. This was through the creation of a confudion matrix with four sections, i.e the True Positive, False Positive, True Negative, and the False Negative. We then went ahead to differentiate between the Recall and the Precision and how to find the optimal points for the 2 using the Classification Threshhold node. We then went ahead to calsulate the mean of the recall and the precision which gave us the F1 measure.

The data was then classified into Binary (either 5 or not 5) and multiclass (0-9). We then computed the different scores for the 2 classes to obtain the best average to use. We were able to compute the averages (Macro F1, Micro F1, and the Weighted F1) and compared the results for the best average to use.

Finally, we did an evaluation of the model using the test data and computed the Macro F1. We then deployed the algorithm using Integrated deployment.



# Attached is the workflow for the MNIST project, the train dataset, and the test data set. Also the captured MNIST project for deployment.
