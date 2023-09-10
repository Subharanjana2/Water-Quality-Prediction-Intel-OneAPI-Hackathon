# Water-Quality-Prediction-Intel-OneAPI-Hackathon
Problem statement:
Freshwater is one of our most vital and scarce natural resources, making up just 3% of the earth’s total water volume. It touches nearly every aspect of our daily lives, from drinking, swimming, and bathing to generating food, electricity, and the products we use every day. Access to a safe and sanitary water supply is essential not only to human life, but also to the survival of surrounding ecosystems that are experiencing the effects of droughts, pollution, and rising temperatures. Participants interested in this theme shall use the below mentioned dataset to check the suitability of water for consumption.

The given dataset serves as a valuable resource for this purpose. By leveraging advanced analytics and predictive modeling, we can evaluate the quality of water based on a range of crucial parameters, allowing us to make informed decisions about its fitness for human consumption. The suggested solution offers comprehensive exploration of various machine learning models and techniques applied to this dataset. From Logistic Regression to Random Forest, Passive Aggressive Classifier, Decision Tree Classifier, AdaBoost, and Neural Network, each model plays a role in evaluating water quality. These analyses offer valuable insights into the performance and effectiveness of different machine learning approaches in solving this critical real-world problem.
# Role of Intel® AI Analytics Toolkit (AI Kit)
During the Intel OneAPI hackathon, the Intel Toolkit empowered us to tackle complex problems more efficiently compared to the regular sklearn library. Its comprehensive set of tools and optimizations allowed us to harness the full potential of modern hardware, achieving significant performance gains and accelerating my project's development.
# Data analysis, visualization and preprocessing:
The provided dataset comprises of 5,956,842 data points, with 23 feature columns and 1 target column showing target label (sustainability of sample).

Now, let's take a closer look at the columns:

Index: A unique identifier for each row.
pH: A numerical value representing the pH level of the water.
Iron: A numerical value representing the iron content in the water.
Nitrate: A numerical value representing the nitrate content in the water.
Chloride: A numerical value representing the chloride content in the water.
Lead: A numerical value representing the lead content in the water.
Zinc: A numerical value representing the zinc content in the water.
Color: Categorical data describing the color of the water, such as "Colorless," "Faint Yellow," etc.
Turbidity: A numerical value representing the turbidity of the water.
Fluoride: A numerical value representing the fluoride content in the water.
Copper: A numerical value representing the copper content in the water.
Odor: A numerical value or categorical data describing the odor of the water.
Sulfate: A numerical value representing the sulfate content in the water.
Conductivity: A numerical value representing the electrical conductivity of the water.
Chlorine: A numerical value representing the chlorine content in the water.
Manganese: A numerical value representing the manganese content in the water.
Total Dissolved Solids: A numerical value representing the total dissolved solids in the water.
Source: Categorical data indicating the source of the water, such as "Lake," "River," "Ground," etc.
Water Temperature: A numerical value representing the water temperature.
Air Temperature: A numerical value representing the air temperature.
Month: Categorical data indicating the month when the data was recorded, such as "January," "November," etc.
Day: A numerical value representing the day when the data was recorded.
Time of Day: A numerical value representing the time of day when the data was recorded.
Target: A binary categorical variable (0 or 1) indicating whether the water quality is suitable (1) or unsuitable (0) for consumption.
PREPROCESSING
Dealing with null values:
Filling null values with the mode (most frequent value) is a common practice in data preprocessing, and it's often used when dealing with categorical or discrete data. Here are some reasons why filling null values with the mode is a reasonable approach: • Preservation of Data Distribution • Handling Categorical Data • Simplicity and Robustness • No Assumption of Linearity • Interpretability
# Feature Scaling:
MinMax scaling is applied to standardize the feature values within a specified range.
# Models
The following models were employed to capture varying tendencies of the dataset. Each model brings something new to the table and its interesting to observe some models perform significantly better than others. This is due to the nature of the dataset. • Neural Networks (NN) Neural Networks, often referred to as deep learning models, have gained prominence in machine learning due to their ability to handle complex, high-dimensional datasets effectively. They are a powerful choice for various tasks, including predicting water quality based on multiple water parameters.

• Logistic Regression

Logistic Regression is often employed as a baseline model in machine learning projects, serving as a benchmark against which the performance of more complex models can be compared. It offers interpretable metrics like precision, recall, and F1-score, which are crucial for assessing a binary classification model's effectiveness.

• Decision Tree Classifier

The Decision Tree Classifier is a versatile machine learning algorithm that can be used for both classification and regression tasks. In this analysis, we explore its application in predicting water quality suitability for consumption based on various water parameters.

• Random Forest Classifier

Random Forest is a robust ensemble algorithm that combines multiple decision trees to improve predictive accuracy and reduce overfitting. It's a suitable choice for this task due to its ability to handle complex datasets with multiple features, making it well-suited for predicting water quality based on various water parameters.

• Voting Classifier

The code introduces an ensemble modeling approach that combines the power of two machine learning algorithms, Decision Trees and Random Forests, in a Voting Classifier. This ensemble technique is employed to enhance the predictive accuracy and robustness of the model. The Decision Tree and Random Forest algorithms are chosen due to their individual strengths and complementarity in handling different aspects of the data.

• XGBoost XGBoost is a popular and powerful machine learning algorithm that is widely used for classification and regression tasks. It stands for eXtreme Gradient Boosting and is an implementation of gradient boosting machines. XGBoost is known for its speed and performance, as well as its ability to handle large datasets and high-dimensional feature spaces. It has been shown to achieve state-of-the-art results on a variety of machine learning tasks, making it a popular choice among data scientists and machine learning practitioners

• AdaBoost Classifier

The AdaBoost Classifier is an ensemble machine learning algorithm known for its ability to improve the performance of weak classifiers. In this analysis, we explore its application in predicting water quality suitability for consumption based on various water parameters.


# Based on these metrics, the XGBoost and Decision Tree models appear to perform exceptionally well, achieving perfect scores in many metrics.
In summary, the Intel OneAPI Toolkit offered a comprehensive suite of tools and libraries that were finely tuned for Intel hardware. This gave you a significant advantage during the hackathon by improving performance, enabling parallelism, and providing detailed insights into your code's efficiency. While sklearn is a valuable library for machine learning and data analysis, it may not offer the same level of hardware-specific optimizations and parallel computing capabilities that the Intel Toolkit provides, making it a powerful choice for high-performance computing and accelerated development in specific domains.









