# Dog Breed Prediction

In this project, we built a Convolutional Neural Network using Keras and TensorFlow to identify the breed of a dog in an image. This is a multiclass classification problem where we focused on three specific dog breeds due to computational limitations.

## Project Setup

1. Upload Kaggle API key:
    - Run the provided code snippet to upload your Kaggle API key.
2. Install Kaggle API client:
    - Use `!pip install -q kaggle` to install the Kaggle API.
3. Download and prepare the dataset:
    - Connect to Kaggle, search for the dataset, download, and unzip it.
4. Data Preprocessing:
    - Load and preprocess the images for the selected dog breeds.
5. Model Building:
    - Create a CNN model using Keras with specific layers and configurations.
6. Training the Model:
    - Split the data into training and validation sets and train the model.
7. Evaluation:
    - Evaluate the model on the test set and visualize the accuracy.
8. Prediction:
    - Make predictions using the trained model and compare them with the actual labels.

## Important Files

- `dog_dataset/labels.csv`: Contains information about the dog breeds.
- `dog_dataset/train/`: Directory with dog images for training.

## Model Summary

- Total Parameters: 162,619
- Optimizer: Adam(0.0001)
- Loss Function: Categorical Crossentropy

## Conclusion

We successfully built a model for dog breed prediction and achieved an accuracy of [insert accuracy here]% on the test set. This model can be further optimized by tuning hyperparameters for improved performance.

This project can be beneficial for organizations working with animal welfare and for educational purposes.