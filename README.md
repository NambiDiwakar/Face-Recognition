# Face-Recognition

# part-1
In Face_data_collection.ipynb file contains Python Script that captures images From Webcam vedio stream
This collecting of all images from the image frame is using haarcascades and storing the face informaton into numpy arrays

The Process in file is explained Below:
1. Read and show video stream, capture images
2. Detect Faces and show bounding box (haarcascade)
3. Flatten the largest face image(gray scale) and save in a numpy array
4. Repeat the above for multiple people to generate training data


# part-2
In Face_recognition Using KNN.ipynb file contains python script using KNN classification algorithm 

Procees is as follows:
1. load the training data (numpy arrays of all the persons)
		x- values are stored in the numpy arrays
		y-values we need to assign for each person
2. Read a video stream using opencv
3. extract faces out of it
4. use knn to find the prediction of face (int)
5. map the predicted id to name of the user 
6. Display the predictions on the screen - bounding box and name

