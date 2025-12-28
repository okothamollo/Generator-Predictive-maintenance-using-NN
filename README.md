This assignment utilizes neural network to build machine learning models for predictive maintenance of generators thereby avoiding high cost associated by replacement. The objective is to build various classification models, tune them, and find the best one that will help identify failures so that the generators could be repaired before failing/breaking to reduce the overall maintenance cost

Model selection

Neural network model with Adam as optimizer and dropout [0.4,0.2] as regularization was selected since it has the highest recall of 98.93% hence best in addressing false negative associated with high replacement cost

Key Insights from the model

•	We have built a model that can be used to predict failures so that the generators could be repaired before failing/breaking to reduce the overall maintenance cost.

•	The model accurately classifies instances with minimal false negatives which have the highest maintenance cost in terms of replacement cost hence significantly reducing maintenance cost.

•	The company can deploy the final model from this exercise to identify with a reasonable degree of accuracy whether failures will occur or not, and this process seems to be easier and more time-efficient than other methods

•	The model could be continuously trained on large data to enhance its performance.

Learnings:

Learned how to conduct effective exploratory data analysis (EDA) and preprocess large sensor datasets to prepare them for modeling. Building and evaluating neural network classifiers taught me the importance of choosing appropriate activation functions and minimizing classification errors, especially false negatives. I also gained experience in interpreting model results and translating insights into actionable recommendations for predictive maintenance, ultimately supporting cost-efficient wind turbine operations.
