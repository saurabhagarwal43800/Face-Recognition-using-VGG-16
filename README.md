# Face-Recognition-using-VGG-16

<img src="/imgs/facial-recog-thumb.png" width="500" alt="Face Thumb">

__Transfer learning (TL)__ is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.  
For example, the knowledge gained while learning to recognize cars could apply when trying to recognize trucks.  

__VGG16__ is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes. It was one of the famous model submitted to ILSVRC-2014. It makes the improvement over AlexNet by replacing large kernel-sized filters (11 and 5 in the first and second convolutional layer, respectively) with multiple 3×3 kernel-sized filters one after another. 

<img src="/imgs/vgg16.png" width="500" alt="Face Thumb">

### __Project:__  

1. Collect the dataset of face samples of different faces in train and test folders with a different folder for each face  
2. Use any Model to train your dataset using Transfer Learning  
3. Recognize the faces by using your model  

### __Prerequisite before Practical:__  

List of Python libraries need to be installed:  
tensorflow  
keras  
opencv  
pillow  
numpy  

*conda install tensorflow keras opencv-python pillow numpy*  

### Implementation:  

Go to your jupyter notebook and write code:  

__STEP 1:__ Collecting the dataset for faces  
__STEP 2:__ Loading the VGG-16 Model and freezing all layers  
__STEP 3:__ Add the Fully Connected Head back onto VGG-16  
__STEP 4:__ Loading our Face Data Set  
__STEP 5:__ Training out model  
__STEP 6:__ Loading our Classifier  
__STEP 7:__ Testing our classifier on some test images  
 
After researching and training the models out of RESNET, Inception, MobileNet and VGG, VGG gives the best accuracy and predictions in my Data Set. My model predicted 9/10 images correctly which makes my model approximate 90% accurate.
