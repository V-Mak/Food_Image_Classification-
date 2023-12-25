# Food_Image_Classification-

* Overview:
This project focuses on food image classification using the Food-101 dataset, a comprehensive collection of 101 food categories, each containing 1,000 images. The goal is to develop and evaluate various machine learning models to accurately classify different food items.

## Project Structure:
*Custom Pizza-Steak Image Dataset Creation:
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
* Transfer Learning and Fine-Tuning:
* Feature Extraction with varying percentages of training data and augmentation.
* Fine-tuning experiments on selected models using different proportions of the dataset.
* Fine-tuning experiments extended to the entire dataset.
* Full Food-101 Dataset Implementation:

* Results:
Comparative analysis showcasing the impact of data augmentation, transfer learning, and fine-tuning on classification accuracy.
* Conclusion:
Summarizes the findings, discussing the effectiveness of various techniques employed and their implications for food image classification tasks.
* Technologies Used:
Python, TensorFlow, Keras, google colab
