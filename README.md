# bird-species-prediction
In this project, I created a convolutional neural network which predicts the different species of a bird. 

I used different layers and other hyperparameters for building, training and testing this multiclass classification model. 

I used Keras for this project. 

## Scope
This project can be used for educational purposes to get a better understanding of how to create network archtecture for a CNN model. 

We can further tune the hyperparameters of this model to reach higher accuracy. It can also be used by bird sancturies to identify different types of birds. 

## Steps
1. Mounting google drive on collab notebook. 
2. Visualizing the images that we will be working on. 
3. Analyziung the dimensions to verify if all images have same dimensions.
4. Converting the images into numpy array and normalize them. 
5. Checking class imbalance. 
6. Splitting the data and performing one-hot encoding. 
7. Creating the model architecture, compiling the model and then fitting it. 
8. Plotting the accuracy and loss against each epoch. 
9. Preprocessing the test data and make predictions on it. 
10. Visualizing the original and predicted labels for the test images. 

## Technology
1. Python
2. Keras
3. Tensorflow

## Accuracy Curve
![image](https://user-images.githubusercontent.com/50231750/202908668-69a08861-fac8-4f94-845f-5e50c407e891.png)

## Loss Curve
![image](https://user-images.githubusercontent.com/50231750/202908675-149158b4-8044-4dc0-9761-172f77d541f1.png)

## Prediction
![image](https://user-images.githubusercontent.com/50231750/202908715-1448844e-0674-4be8-aba9-0e1dc2fe8f27.png)

## Conclusion
We started with loading the dataset into google colab using google drive and visualizing the images. Normalizing is an important step when working with any type of dataset. After that we created a CNN Model which is further used for predicting the bird species using the image supplied to model.
