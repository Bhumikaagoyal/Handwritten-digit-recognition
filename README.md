# Handwritten-digit-recognition
This project aims to build a handwritten digit recognition system using the Support Vector Machines (SVM) algorithm. Handwritten digit recognition is a fundamental problem in pattern recognition and machine learning, with applications ranging from postal automation to optical character recognition in electronic documents.

Dataset:

We utilize the popular MNIST dataset, which contains 70,000 images of handwritten digits (0 through 9). Each image is a grayscale 28x28 pixel, representing a digit. We load the dataset using scikit-learn's load_digits module.

Visualization:

To understand the dataset better, we visualize a subset of the images using matplotlib. This step helps in gaining insights into the structure of the data and the challenges it presents.

Preprocessing:

Before feeding the data into the SVM model, we preprocess it by reshaping the images into a flat array of pixel values. This transformation allows us to treat each image as a single data point with multiple features.

Model Training:

We split the dataset into training and testing sets using scikit-learn's train_test_split function. Then, we train an SVM classifier with a linear kernel on the training data. The linear kernel is chosen for its simplicity and effectiveness in this context.

Evaluation:

Once the model is trained, we evaluate its performance on the test set using various metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into how well the model generalizes to unseen data.

Conclusion:

By leveraging SVM, we demonstrate a reliable approach to handwritten digit recognition. The trained model can accurately classify digits from unseen images, showcasing the power of machine learning in solving real-world classification problems.

Dependencies:

Python 3.x
NumPy
scikit-learn
Matplotlib
Feel free to explore the code and experiment with different parameters to improve the model's performance!
