# Image-Classification
#Purpose  

Data collection, statistical analysis, interpretation and image classification of the obtained diseases images  are the focus of this project, as well as the exploration of quantitative methods for analysing this data using machine learning (support vector machine, fully connected neural network, convolutional neural network, K-nearest neighbour, decision tree, logistic regression). Six machine learning models will be created, tested, and compared to see which worked best for imagine classification. 

#Scope 

The project's primary emphasis is on cleaning and pre-processing all of the photos, including coding to remove duplicates, convert from PNG to JPEG format, normalise and scale the images, and extract features based on HOG values. The classifiers will be trained using the extracted features, and then evaluated using 10 rounds of cross validation. In order for the trained classifiers to determine which class this picture belongs to, the hyperparameters of the classifiers will be fine-tuned and the features from the test dataset will be input into the model. The remainder of the paper will show and assess the findings obtained from the classifiers and models, provide suggestions for the best models and classifiers based on the analysis, and provide ideas for increasing the efficiency of the classifiers and models. Support vector machine, decision tree, Logistic regression, K-Nearest neighbour, Convolutional Neural Network, and full connected neural network are just some of the linear and non-linear classifiers used in this paper.

#Background Information Of Image Dataset 

This project's image classification method makes use of a disease-related image dataset including x-ray images of persons with tuberculosis, covid 19, and pneumonia. The disease dataset was obtained from Kaggle.com. After data cleaning and pre-processing, 448 photos were retained from the original 1500; this yielded 149 images for covid19, 149 for pneumonia, and 150 for tuberculosis.  Images will serve as instances, while pneumonia, tuberculosis, and covid19 will serve as labels, in this image categorization task.
