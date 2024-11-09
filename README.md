In this project, I have developed a machine learning model to optimize banking marketing campaigns aimed at attracting more customers to subscribe to term deposits. The dataset used for this project contains information on past marketing campaigns, including customer demographics, campaign features, and whether the customer subscribed to a term deposit.

Objective:
The primary objective of the project was to build a model that can predict the likelihood of a customer subscribing to a term deposit based on various factors. A term deposit is a fixed-rate deposit offered by banks and financial institutions, where a customer's money is locked for a specified maturity period, typically offering better interest rates compared to regular deposit accounts.

Model Architecture:
The model is a sequential neural network built using Keras, with the following layers:

Dense Layer 1:

16 units with ReLU activation.
This layer accepts the input features and learns non-linear representations of the data.
Dense Layer 2:

10 units with ReLU activation.
This hidden layer further processes the learned features from the previous layer, allowing the model to capture more complex patterns.
Output Layer:

1 unit with Sigmoid activation.
This output layer is designed for binary classification (subscribed or not subscribed). The Sigmoid function outputs a probability value between 0 and 1, indicating the likelihood of subscription.
Model Summary:
Total Parameters: 453
Trainable Parameters: 453
Non-Trainable Parameters: 0
Key Features:
The model was trained on customer data, including features such as age, job type, marital status, previous campaign interactions, and contact details.
Binary Classification: The target variable is whether the customer subscribed to a term deposit (1 for subscribed, 0 for not subscribed).
Achievements:
The model was successfully trained to predict customer behavior and optimize marketing campaign strategies.
By predicting which customers are more likely to subscribe, the model can help financial institutions target their marketing efforts more effectively, thus improving customer acquisition and engagement with term deposit products.
Future Enhancements:
Exploring hyperparameter tuning and optimization techniques to further improve the model's performance.
Experimenting with additional features such as customer income, credit score, and previous account activity to increase prediction accuracy.
