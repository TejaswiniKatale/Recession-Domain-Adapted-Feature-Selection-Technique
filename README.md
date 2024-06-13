 Existing feature selection algorithms often choose features based on their individual importance and consider them as independent entities, which may overlook underlying interrelationships amongst the features within themselves.
 This may result in overfitting as only highly correlated features are selected without considering their collective contribution. Hence it is crucial to take into account both individual feature importance and feature interactions. 
 To mitigate this issue, this research paper proposes a Novel Methodology of Domain Wise feature selection approach which is capable of identifying the interrelationships by focusing on Domain-Wise feature selection. It ensures that correlated and
 similar features are considered together and is implemented on a Recession Dataset consisting of 293 observations and 45 features. It groups similar features in 8 domains and further arranges them in descending order of Average Correlation
 values. For each mini dataset it considers only those data points which are nearest to the mean of that domain and merges all unique observations from these domains and creates a new dataset. Further applying Preprocessing steps
Outlier Elimination, Upsampling and Feature Selection. This paper also discusses how the order of preprocessing can impact the overall result of the evaluation metrics. The efficacy of the algorithm is checked by the accuracy scores of
 Random Forest-99.16%, Logistic Regression-98.05%, XGBoost-98.05%, Static Probit Model-97.5%, Decision Tree-96.9%, and SVM-94.4%. Therefore, by considering both the significance of individual features and the relationships between 
 them the suggested approach successfully addresses the shortcomings of traditional feature selection algorithms.
