# Increase-Stochastic-Gradient-Descent-SGD-Classifier-s-accuracy-by-adding-shifted-images-Trained-Set

### With this research Project, my goal is to create system software that, by using shifted photos in the training set, will increase the accuracy of the Stochastic Gradient Descent (SGD) Classifier. 

**I planned to make a basic Python function that will help to shift photos in different directions in order to build a useful program.**

**By Shifting images, we can expand the quantity of training data that the business has access to, which could improve our model's accuracy.**


### 1. Load Data 

**Load the mnist data from the scki-kit (sklearn) library and look at one of the images in the dataset.**

**Note: The goal of this group work is solely to understand how to shift an image thus, you are not required to split the dataset as you would only focus on a few digits in the dataset.**
 

### 2. Shifting Images 

**Hint: To shift images we can use the shift function from scipy.ndimage.interpolation**


### 2.1 Shift Image Up 

**Pick an image from the dataset and view it.** 

**Now write a function to shift the image up by 1 pixel (You can test your function by shifting the image up by about 5 pixels and viewing it to observe the change in the digits position)**


### 2.2 Shift Image Down 

**Pick an image from the dataset and view it.** 

**Now write a function to shift the image down by 1 pixel (You can test your function by shifting the image down by about 5 pixels and viewing it to observe the change in the digits position)**


### 2.3 Shift Image Right 

**Pick an image from the dataset and view it.** 

**Now write a function to shift the image right by 1 pixel (You can test your function by shifting the image to the right by about 5 pixels and viewing it to observe the change in the digits position)**


### 2.4 Shift Image Left 


**Pick an image from the dataset and view it.** 

**Now write a function to shift the image left by 1 pixel (You can test your function by shifting the image to the left by about 5 pixels and viewing it to observe the change in the digits position)**



---------------------------


### In this second project, my main goal is to develop software that, by using shifted photos in the training set, would increase the accuracy of the stochastic gradient descent (SGD) classifier. 
As a result, this program ought to assist in expanding the variety of data that the organization has available to train the model, which will enhance accuracy.   


### 1. Load Data 

**Load the MNIST dataset from sklearn**


### 2. Data Preparation 


**Split the dataset into 2 parts: training set for training the model and test set for evaluating the model's performance on unseen data.**


### 3. Expand Training Data 


**Use the functions from the previous group work to increase the size of the training set by adding new digits with values that have been shifted to the left, right, up or down by 1 pixel.** 

**Note: This process should result in your training set being 5 times more than it was previously.**


### 4. Modelling 


**Train your model on the training set and use cross validation to evaluate the model's training performance.** 

**Plot a confusion matrix to visualise the model's prediction performance for each of the digit classes in the dataset** 

**Test the accuracy of your model on unseen data and evaluate its performance by cross validating the model.** 





