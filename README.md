# infi
For training our model I used the latest yolo, that is yolov5.
Training was done on google colab, since my system did not meet the configuration requirements.



Main file contains all the necessary code.

First thing first. this is step by step what i did:
1. Downloading the dataset.
2. pre-processing in a proper format that yolo model understands
3. arranging the folders in format given by yolo(images and labels)
4. Normalizing the annotation as per the yolo standards and seperating the annotation for each image file.
5. creating a data file as data.yaml, to give all the information for the yolo model about the dataset.
6. Next is cloning the yollo data, and installing all the requirements in a closed environment.
7. Now the most important thing training the model on train datasets,and validating/testing the model on valid/test datasets and saving the weights after training.
8. now predicting the model on test images and saving the predicted values.
9. image to product values are attached in the file along with the learning metrics.

steps 6-9 are in main file.
