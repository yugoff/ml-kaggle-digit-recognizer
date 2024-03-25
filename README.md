# ml-kaggle-digit-recognizer

## Computer vision fundamentals with the famous MNIST data

Competition Description
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

### I will describe in stages what is done in the laptop.

1. Imported the libraries we need, such as numpy, pandas, matplotlib and sklearn.
2. Extract the pixel value from the data to view the data as images.
3. Divided the data into training and test samples.
4. Created a model using tens or flow.karas, used two convolutional layers with relu activation, two puddings after each layer, pulled everything into one vector and added two fully connected layers, then compiled the model to determine important parameters during training, determining the loss function, as well as determining the accuracy of the model.
5. Then I trained the model on 100 epochs, which showed slightly better results than 10 epochs, and looked at the results using plt.
6. I also extracted pixel features from the test images to see the result after predicting the model and extracted it all into the predictions file.
