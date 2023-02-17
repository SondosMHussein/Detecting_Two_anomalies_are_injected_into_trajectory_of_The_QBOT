# Detecting 2 different anomalies are injected into the trajectory of the QBot. 

# Description
The main objective of this assignment is to detect 2 different anomalies are injected 
into the trajectory of the QBot, and thus it supposedly reflects onto the trajectory of 
the QDrone as an anomaly: 

the drone will follow the bot by moving out of the trajectory temporarily, and the bot 
enters a specific area that is a restricted region for the QDrone. we have a dataset from 
a 2-minute experiment. We will extract 4 attributes from the dataset: “follower x 
data”, “follower y data”, “leader x data” and “leader y data” (‘x’ and ‘y’ refers to 
coordinate). We will implement and compare the performance of different machine 
learning algorithms which are SVM, PCA, KNN, and DBSCAN. Then We will plot the 
model results alongside with data and compare unsupervised models with respect to 
accuracy, precision (for both anomaly and normal instances), recall (for both anomaly 
and normal instances) and F1 scores (for both anomaly and normal instances).



#  Conclusion: 
In this project, we need to detect the anomalies injected into the trajectory of the bot, and 
thus, it supposedly reflects onto the trajectory of the drone. Firstly, we implement four 
models which are SVM, PCA, KNN, and DBSCAN to compare between them. After that, 
we plotted the TSNE plot to visualize the result of Qbot and Qdrone in each model. Then 
we compute the evaluation of each model using the true label found in 
Dataset_to_be_used_in_performance_comparison.csv. the results showed that the 
DBSCAN model produce a better accuracy score with 95%. PCA & SVM give an accuracy 
score of 93%. Finally, KNN produce the worst accuracy score with 90%.
