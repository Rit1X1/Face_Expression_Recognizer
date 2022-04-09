# Face_Expression_Recognizer
Python-program

This repository includes deep learning based project implementations I've done from scratch. You can find both the source code and documentation as a step by step tutorial. Model structrues and pre-trained weights are shared as well.

Facial Expression Recognition Code

This is a custom CNN model. Kaggle FER 2013 data set is fed to the model. This model runs fast and produces satisfactory results. It can be also run real time as well.

4.1. Install dependencies
Tensorflow
Tflearn
Numpy
Argparse
[optional] Hyperopt + pymongo + networkx
[optional] dlib, imutils, opencv 3
[optional] scipy, pandas, skimage
Better to use anaconda environemnt to easily install the dependencies (especially opencv and dlib)

4.2. Download and prepare the data
Download Fer2013 dataset and the Face Landmarks model

Kaggle Fer2013 challenge
Dlib Shape Predictor model
Unzip the downloaded files

And put the files fer2013.csv and shape_predictor_68_face_landmarks.dat in the root folder of this package.

