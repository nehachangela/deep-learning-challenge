# deep-learning-challenge

The primary objective of this project is to leverage machine learning and neural network techniques to develop a binary classifier that assists Alphabet Soup, a nonprofit foundation, in the selection of funding applicants with the highest likelihood of success in their ventures. Alphabet Soup aims to streamline its funding allocation process by utilizing predictive modeling to identify organizations that align with its goals and have a greater chance of achieving positive outcomes from the funding provided.

**Alphabet Soup Deep Learning Model Performance Report**

**Overview of the Analysis:**
The purpose of this analysis is to create a deep learning model using a neural network to predict the success of charitable organizations in Alphabet Soup. The dataset and the target variable is 'IS_SUCCESSFUL,' indicating whether a charity is successful or not.

**Results:**

**Data Preprocessing:**

- **Target Variable:**
  - Target variable: 'IS_SUCCESSFUL'

- **Features:**
  - Features include one-hot encoded categorical variables in the dataset and the binarized 'IS_SUCCESSFUL' target variable.

- **Removed Variables:**
  - 'EIN' and 'NAME' columns were removed from the input data as they are neither targets nor features.

**Compiling, Training, and Evaluating the Model:**

- **Neural Network Architecture:**
  - The neural network model consists of an input layer with 80 neurons (equal to the number of input features), a hidden layer with 30 neurons, respectively, and an output layer with 1 neuron and a sigmoid activation function for binary classification.

- **Target Model Performance:**
  - The model achieved an accuracy of 72.3% on the test set.

- **Steps to Increase Model Performance:**
  - Adjusted the neural network architecture by experimenting with the number of layers and neurons.
  - Tuned hyperparameters, including learning rate and batch size.
  - Conducted feature engineering to identify potential new features that could improve predictive power.

**Summary:**
The deep learning model achieved a decent accuracy of 72.3%. However, the target accuracy of 75% was not reached. To further enhance model performance, I would like to continue experimenting with different model with architectures, hyperparameters, and feature engineering techniques. Additionally, considering the nature of the dataset, other machine learning algorithms, such as ensemble methods (e.g., Random Forest ), could be explored to identify the most effective model for this classification problem.
