# Food-Image-Recognition-Calorie-Estimation
Food image classification using MobileNetV2 and estimated calorie information

## Project Overview
This project uses deep learning to recognize food images and provide approximate calorie information for selected food categories.

## Objective
To classify food images into food categories using a pretrained MobileNetV2 model and display estimated calories for supported foods.

## Technologies Used
- Python
- TensorFlow and Keras
- TensorFlow Datasets
- MobileNetV2
- NumPy and Matplotlib
- Google Colab

## Dataset
The project uses the Food-101 dataset. A subset of the training and validation data is used to reduce training time. The dataset is downloaded through TensorFlow Datasets when the notebook is executed.

## Methodology
1. Load and preprocess food images.
2. Use a pretrained MobileNetV2 model for feature extraction.
3. Train a classification layer to identify food categories.
4. Evaluate the model on test images.
5. Display the predicted food category and confidence.
6. Show approximate calorie information for supported categories.

## Calorie Estimation
The project includes a small lookup table for selected food categories. Calorie values are approximate estimates and may vary depending on serving size, ingredients, and preparation method.

## Results
The notebook displays the model's test accuracy, training graphs, and sample predictions. Refer to the notebook output for the actual results.

## How to Run
1. Open the notebook in Google Colab.
2. Run the installation and import cells.
3. Load the dataset and preprocess the images.
4. Train and evaluate the model.
5. Test the model using a sample food image.

## Note
The model is trained using a limited subset of Food-101 for demonstration. Predictions and calorie estimates should not be treated as professional nutritional advice.
