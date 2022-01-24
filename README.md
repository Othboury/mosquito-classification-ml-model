# mosquito-classification-ml-model

My Master's research subject in the University of Toulon was: "Mosquito presence detector by passive acoustics using a mobile phone".

This project highlights the creation, training and evaluation of a Machine Learning model, based on Keras & Tensorflow, aiming at predicting the the sound type of a record and define its class type (mosquito - background -audio).

The DataSet used in this project is the same used in "HumBugDB: A Large-scale Acoustic Mosquito Dataset". In order to run the model or to remodel it to your needs, it's necessary to download the audio recordings from here: https://zenodo.org/record/4904800#.Ye6TWurMJPY

It this project you will also find steps to deploy the model in AWS.

This project is linked to: https://github.com/Othboury/audio-recorder-aws-s3upload, which us the mobile application that record the audios send them to the model and receive the classification in order to present it to the user.
