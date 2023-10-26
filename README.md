# 🩺 Patient_survival_prediction - Using Artificial Neural Network

## 🧾Description: 
Getting a rapid understanding of the context of a patient’s overall health has been particularly important during the COVID-19 pandemic as healthcare workers around the world struggle with hospitals overloaded by patients in critical condition. Intensive Care Units (ICUs) often lack verified medical histories for incoming patients. A patient in distress or a patient who is brought in confused or unresponsive may not be able to provide information about chronic conditions such as heart disease, injuries, or diabetes. Medical records may take days to transfer, especially for a patient from another medical provider or system. Knowledge about chronic conditions can inform clinical decisions about patient care and ultimately improve patient's survival outcomes

## 🧭 Problem Statement: 
The target feature is hospital_death which is a binary variable. The task is to classify this variable based on the other 84 features step-by-step by going through each day's task. The scoring metric is Accuracy/Area under ROC curve.

# Project Flow

### Data Collection: 
Data collection for this healthcare task involves gathering information from patients admitted to hospitals, especially in the context of the COVID-19 pandemic. This data includes 84 features such as patient demographics, medical history, and current health status. The primary goal is to classify the binary variable "hospital_death" to aid healthcare workers in making critical decisions, ultimately improving patient survival outcomes, with accuracy and the area under the ROC curve as the evaluation metrics.

### Data Preprocessing:
Cleaned and preprocessed the data, which involved handling missing values.

### Feature Engineering:
Performed Feature Engineering, Which involved the Encoding Techniques like One hot Encoding for Categorical features,feature scaling - Standardizing.

### Model Building:
So far, I've built three deep learning models for the classification task. In the first model, I created a basic deep learning architecture to predict the "hospital_death" variable. In the second model, I addressed the challenge of class imbalance by assigning different weights to the classes, prioritizing the class with fewer samples. This helped improve the model's performance in handling imbalanced data.

### Model Tunning:
In the third model, I leveraged Keras Tuner to fine-tune hyperparameters, focusing on minimizing the loss values for both training and validation data. 
This approach enhanced the model's stability and performance. The conclusion from the final model is that the validation loss significantly decreased, precision and recall metrics improved to some extent, and the model became more generalized. The choice of learning rate and the number of units in the layers was made using proper methods, ensuring a more robust and efficient deep learning model for this critical healthcare classification task.

![image](https://github.com/Kamalesh1512/patient_survival_prediction-ANN/assets/81355463/6cd86d4b-8d97-487a-9011-15454f30195a)
