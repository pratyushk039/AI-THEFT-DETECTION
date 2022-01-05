# AI-THEFT-DETECTION
QUESTION1 :
Which Neural network and why 

ANSWER:
Neural Network we used is CNN i.e Convolutional Neural Network.
CNNs are used for image classification and recognition because of its 
ability to process multidimensional matrices(ANN, on the contrary is 
built for processing single column vectors) . The CNN follows a 
hierarchical model which works on building a network, like a funnel, 
and finally gives out a fully-connected layer where all the neurons 
are connected to each other and the output is processed. Keeping all 
the above things in mind we used CNN for our project.



QUESTION 2:
Which Optimizer and why 

ANSWER :
Optimizer we used is adam which is a replacement optimization 
algorithm for stochastic gradient descent for training deep learning 
models. We chose this because adam optimizer combines the best 
properties of the AdaGrad and RMSProp algorithms to provide 
optimization algorithm that can handle sparse gradients on noisy 
problems . This efficacy against noise-hindrance seals the deal
,because photos can contain a lot of visual noise. Also it relatively 
easy to configure where the default configuration parameters do 
well on most of the problems. Also when we want to train neural 
network in less time and more efficiently ,Adam is the best choice. 
Hence we Chose Adam for our project.


QUESTION 3:
Which Accuracy metric and why 

ANSWER:
Accuracy metric we used is accuracy. It calculates how often 
predictions equal labels. This metric creates 2 local variables , total 
and count that are used to compute the frequency with which 
y_pred matches y_true. This frequency is ultimately returned as 
binary accuracy : an idempotent operation that simply divides total 
by count . Hence this was the best choice for our project training.


QUESTION 4:
Which loss function and why

ANSWER:
The loss function we used is categorical_crossentropy . Categorical 
crossentropy is a loss function that is used in multi-class classification 
tasks. These are tasks where an example can only belong to one out 
of many possible categories, and the model must decide which one .
Since our project is based on multiclass classification we used 
categorical_crossentropy loss function for our project.


QUESTION 5:
Brief information on how the cleaning / pre-processing was done 

ANSWER:
For the preprocessing part we performed Normalization on our data .
Normalization is a technique applied as part of data preparation . 
We performed normalization to change the values of numeric 
columns in the dataset to use a common scale in the range[0,1] , 
Without distorting differences in the ranges of values or losing 
information.


QUESTION 6:
How data was got into the right shape

ANSWER:
After normalizing the input data , we bring the data into the right 
shape by using np.reshape function which gives a new shape to the 
array without changing its data . The reshape() function takes a 
single argument that specifies the new shape of the array . Using this 
we brought our data into right shape.


QUESTION 7:
What functions/features of OpenCV were used.

ANSWER:
OpenCV functions we used in our project are:
- VideoCapture() : To get a video capture object for the camera.
- cvtColor() : To convert color of an image from one color space to 
another.
- color_BGR2GRAY() : To convert Image from color to grayscale 
format.
- resize() : Changes the dimensions of an image (height, width).
- Cascade_classifier() : It is a machine learning based approach where 
a cascade function is trained from a lot of positive and negative 
Images . It is then used to detect objects in other images.
- detectMultiScale() : Detects objects of different sizes in the input 
image. The detected objects are returned as a list of rectangles.
- rectangle() : Used to draw a rectangle on any image.
- imshow() : Shows the frames in the video.
- destroyAllWindows() : Simply destroys all the windows we created.
- cv2.putText() : Used to draw a text string on any image.


QUESTION 8 : 
Which dataset have you used ? or if generated data using webcam 

ANSWER :
For our project we have generated data using webcam 
