# Image classifier from scratch using NumPy + CNN + Transfer Learning
### The Jupyter notebook provides an explanation of key concepts such as Gradient Descent, Forward and Backward Propagation, and the Cost Function, all implemented for building a model from scratch.

## Objective
The primary objective of this project is to develop an effective image classification model capable of distinguishing between images of cats and dogs. Initially, the focus was on building a classifier from scratch using basic machine learning techniques and neural networks. However, limitations imposed by a small dataset leads to implementing Transfer Learning and Data Augmentation to enhance model accuracy and generalization. Ultimately, the goal is to achieve high accuracy in classifying pet images, demonstrating the effectiveness of advanced deep learning techniques.

## Methodology
1. Data Preparation: The dataset was divided into two classes (cats and dogs), consisting of images organized into separate folders for training and testing. The data was preprocessed to ensure consistency in size and format.
2. Model Development:
- From Scratch: Initial models were built using NumPy and basic CNN architectures. These models employed convolutional layers, activation functions, and pooling layers.
- Transfer Learning: To improve accuracy, pre-trained models such as VGG16, ResNet50 and InceptionV3 were utilized. This involved freezing the base layers of the model while retraining the final layers on the cat and dog dataset.
3. Training and Evaluation: The models were trained on the training dataset, and their performance was evaluated using the test dataset. Accuracy scores were calculated to assess the models’ effectiveness.

## Summary
In this project, I built a cat and dog image classifier, starting with models from scratch using NumPy. Limited by a small dataset, initial models achieved only around 60% accuracy.
To address this, I used Transfer Learning, which significantly improved performance by leveraging pre-trained models. The InceptionV3 model achieved the highest accuracy at 95%, highlighting how Transfer Learning can effectively boost performance with limited data
