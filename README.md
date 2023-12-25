# Food_Image_Classification-

## Overview:
This project focuses on food image classification using the Food-101 dataset. The Food-101 dataset is a widely used collection of images designed for food recognition and classification tasks in the field of machine learning and computer vision. It consists of 101 food categories, with each category containing 1,000 high-resolution images. This makes a grand total of 101,000 labeled images.The dataset covers a diverse range of food items from various cuisines worldwide, including fruits, vegetables, desserts, main dishes, snacks, and beverages. Each image in the dataset portrays a single food item centered in the picture, making it ideal for training and evaluating computer vision models.

## Project Structure:
* Custom Pizza-Steak Image Dataset Creation:
Created a custom dataset by extracting pizza and steak images from the Food-101 dataset.
Utilized data augmentation techniques to enhance the dataset size and diversity.

* Multi-Class Model Development:
Constructed a multi-class image classification model using a subset of 10 food classes from the Food-101 dataset.
Implemented transfer learning techniques, particularly feature extraction, using pre-trained models.

* Transfer Learning and Data Augmentation:
Explored transfer learning techniques with 10% and 1% of the training data.
Evaluated the impact of data augmentation on model performance using the 1% training data subset.

* Fine-Tuning Models:
Conducted fine-tuning experiments on the models:
Fine-tuned the existing model_3 (Feature Extraction with 10% Training Data and Augmentation) with 10% of the training data.
Fine-tuned the same model with the entire dataset.

* Full Food-101 Dataset Utilization:
Leveraged the entire Food-101 dataset for feature extraction and model training.
Implemented fine-tuning techniques on the feature extraction model to outperform the results mentioned in the DeepFood paper.

## Notebooks Description:

* Custom Pizza-Steak Dataset Creation:
Details the process of creating a custom dataset focusing on pizza and steak images from Food-101.
Demonstrates data augmentation techniques applied to enrich the dataset.
* Feature Extraction with varying percentages of training data and augmentation.
* Fine-tuning experiments on selected models using different proportions of the dataset.
* Fine-tuning experiments extended to the entire dataset.
* Full Food-101 Dataset Implementation:

### Results:
Comparative analysis showcasing the impact of data augmentation, transfer learning, and fine-tuning on classification accuracy.
### Conclusion:
Summarizes the findings, discussing the effectiveness of various techniques employed and their implications for food image classification tasks.
### Technologies Used:
Python, TensorFlow, Keras, google colab
