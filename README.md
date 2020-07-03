# CS175-Distracted-Driver-Detection

#RESNET18 #PYTORCH #MACHINELEARNING

Distracted Driving:
- Suggested as a possible contributor to the increase in fatal crashes from 2014 to 2018 
- Source of growing public concern due to a rise in the use of smart devices

Our data in building detector: (Provided by StateFarm in their Kaggle Challenge: 
- Training data: Contains 22,424 images in the training data separated into 10 labeled class folders
- Testing data: 79.7 thousand unlabeled images (tested for accuracy through kaggle submission)
- Size of each image given to us is 640 × 480 pixels

Our model:
- ResNet18 (had to preprocess image and make a few changes to pyTorch's built in ResNet18)
- Used cross entropy loss and a SGD optimizer with a learning rate of 0.001, a momentum of 0.9, and Nesterov momentum
- Train accuracy of roughly 98%!
- Test accuracy of almost 97%!


Here's a comprehensive explanation of what we did and our report too:
Slides: https://docs.google.com/presentation/d/15rANbhOT-V8eld_5PysMACDmnw2pN_FrsG0ue1Fh0Q4/edit?usp=sharing
Report: https://docs.google.com/document/d/13Rgr5JriOWJEL9ZqDSdEUFkHhNHSRsK-D5Ly_eS1J8U/edit?usp=sharing