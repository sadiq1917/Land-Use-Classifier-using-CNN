# Land-Use-Classifier-using-CNN
A simple Convolutional Neural network that uses transfer learning to classify satellite images into 20 different land features.
This CNN uses the Land-Use scene classification dataset available at:
https://www.kaggle.com/datasets/apollo2506/landuse-scene-classification

File list:
1.  Training.ipynb: The main notebook file used to train and validate the model. It first trains a simple CNN and then uses transfer learning technique to train a final
    model.
2.  Test.ipynb: Notebook file used for testing the model. It first loads the final model and then calculates train accuracy based on the number of correct predictions. 
    It also has a single image testing block that allows you to test a single image by entering its path.
