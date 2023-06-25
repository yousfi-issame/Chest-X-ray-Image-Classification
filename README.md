# Chest X-ray Image Classification using Convolutional Neural Network
Construction of CNN model for detection of pneumonia in x-rays from scratch

The "Chest X-ray Image Classification using Convolutional Neural Network" project focuses on developing a deep learning model to classify chest X-ray images. The goal is to create an efficient and accurate system that can assist in the diagnosis of various thoracic diseases and abnormalities.

The project involves the following key steps:

1- Data Collection: 
    Gather a large dataset of chest X-ray images with corresponding labels indicating the presence or absence of specific conditions such as pneumonia, tuberculosis, or lung cancer. The dataset should encompass a diverse range of cases to ensure the model's robustness.

2- Data Preprocessing: 
    Clean and preprocess the collected images to enhance the quality and remove any noise or artifacts. Perform techniques such as resizing, normalization, and augmentation to standardize the data and increase the model's generalization capability.

3- Model Architecture: 
   Design a Convolutional Neural Network (CNN) architecture tailored for chest X-ray image classification. CNNs are well-suited for image analysis tasks due to their ability to extract meaningful features hierarchically. Experiment with different CNN architectures, such as VGGNet, ResNet, or InceptionNet, to find the most suitable one.

4- Model Training: 
   Split the preprocessed dataset into training, validation, and testing sets. Train the CNN model using the training data, optimizing its parameters through techniques like gradient descent and backpropagation. Regularize the model to prevent overfitting and monitor its performance on the validation set.

5- Model Evaluation: 
   Evaluate the trained model on the testing set to assess its classification accuracy, precision, recall, and F1 score. Analyze the model's performance across different disease categories and explore any potential biases or limitations.

6- Model Optimization: 
   Fine-tune the model by experimenting with hyperparameter tuning, network architecture adjustments, or incorporating advanced techniques like transfer learning or ensembling. Strive to improve the model's performance and robustness.

7- Deployment and Integration: 
   Deploy the trained model into a production environment where it can be utilized for real-time chest X-ray image classification. Develop an intuitive user interface to facilitate interaction with the model and provide accurate predictions. Integrate the system with existing medical systems or applications to enhance diagnostic workflows.

# Use
Use the following command "CMD":
    streamlit run Classifia.py
 Or
 App Deployed on Streamlit Share:
[Link](https://share.streamlit.io/yousfi-issame/memoire/License/Classifia.py)
 

