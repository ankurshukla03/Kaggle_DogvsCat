# Kaggle_DogvsCat

Dataset - From [Kaggle](https://www.kaggle.com/c/dogs-vs-cats)

# Problem Statement
Write an algorithm to classify whether images contain either a dog or a cat.  This is easy for humans, dogs, and cats. Your computer will find it a bit more difficult.

# Training the Model
- From 25000 images I have used 4020 images for [validation](https://github.com/ankurshukla03/Kaggle_DogvsCat/tree/master/validation) while training the model. 2010 images for dog and 2010 images for cat. 
Convolutional Layer: 3, input_shape = (128,128,3), Added Dropout for avoiding over fitting. Dropout rate = 0.5, With these changes acc for validation reached 92%
- Ran another iteration with steps per epochs to 8000 and validation steps to 2000.
- First Submission got 10.11(less is better) when submitted on Kaggle(Not a great score working on improving the model).
- Added a third model which has more Conv2D layer for increasing the accuracy of the model.

# Model
You can find all the code for the model [here](https://github.com/ankurshukla03/Kaggle_DogvsCat/blob/master/Kaggle-DognCat.ipynb)

# Single Image Prediction
Ran the model for single image prediction also.