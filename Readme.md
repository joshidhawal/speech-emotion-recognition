# Emotion Recognition Using Speech

This Project aims to identify the emotion of a person from the recorded speech sample. This will be done with the help of a Neural Network which will be created and run locally. This is a final year project for Bachelor's in Computer Engineering for University of Mumbai.

## Prerequisites

* Data Sets:

1. RAVDESS : You can read about it by following the link : <https://zenodo.org/record/1188976#.XfxCL0czZPY>
2. SAVEE : You can read about it by following the link : <http://kahlan.eps.surrey.ac.uk/savee/>

* Software/Technologies used :

1. Python 3 : Specfically Python 3.6x as Python 3.7 and above have some complications with tensorflow.
2. Tensorflow : Machine Learning Library, we are using the GPU variant here to make things a tad bit faster.
3. Anaconda : We are using Anaconda Environment for the ease of setting things up and keeping them updated. Also some conda custom libraries are faster than usual python stock libraries hence optimisation helps in speed.
4. Keras : A Machine Learning Library based on Tensorflow
5. Some other things : Jupyter Notebook, Visual Studio Code, Numpy, Pandas, SciPy, etc.

## Methodology

1. Observe the Data Audio Waveform and Spectogram along with Mel Spectogram to find out what is important to be extracted as features.
2. Using the Scripts extract the MFCC Features saving each feature set for each audio in a csv file.
3. Combine all the Individual Audio Feature Sets to make a combined Dataset.
4. Clean the Dataset post the merge by using any of the Data Science Methods.
5. Create the Datasets(Test, Train, Validate, etc.) to feed into the model
6. Building the Model
7. Training the Model on Training Data
8. Checking Accuracy using the Test Data
9. Predicting Emotion
10. Creating UI to Give Audio Input and Recieve a Prediction

## References

1. Towards Data Science Article : <https://towardsdatascience.com/speech-emotion-recognition-with-convolution-neural-network-1e6bb7130ce3>
2. Github - Towards Data Science Article : <https://github.com/rezachu/emotion_recognition_cnn>
3. Original Owner Reference Github : <https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer>
