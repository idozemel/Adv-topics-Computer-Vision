# Adv-topics-Computer-Vision
This is the final project of Advanced topics in Computer Vision course. <br>

In this project we are asked to use two diffrent ways to accomplish highest accuracy numbers in image recognition. <br>
We were asked to divide our full dataset into train and test,

# Fist notebook - CNN from scratch <br>
In the creation of CNN network for our project we have tested 4 diffrent scratch networks. <br>
We have changed hyper paraments, data augmentation, added an extra layer, for acomplishing our goal, to get higher accuracy rates.

# Second notebook - Transfer Learning <br>

we have tested 4 diffrent networks.
In each test we ran the same 2extra layers, fully connected layer of 1024 neurons and our exit layer of fully connected 120 neurons using softmax.
In addition of that, we have used the same augmentation on the same data for every run to see the diffrences in every model for every test.

The best model performences is InceptionResNetV2 that got 87.5% accuracy on our test data, not far from him is Xception model with 86.33%.
MobileNet is the worst tested model in our project with only 71.58%! <br>

Transfer learning is definitely going to be one of the key drivers for machine learning and deep learning success in mainstream adoption in the industry. I definitely hope to see more pre-trained models and innovative case studies which leverage this concept and methodology. 

<img src="https://github.com/idozemel/Adv-topics-Computer-Vision/blob/main/class_predict.jpg" alt="class_pred"/>
