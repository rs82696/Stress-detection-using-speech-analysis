Stress Detection in Women Using Speech Analysis

INTRODUCTION
             Modern life is full of stress. Stress is widely recognized as a major problem for women in their daily life. Health and Safety Executive (HSE) have defined stress as the adverse reaction people have to excessive pressure or other types of demand placed on them at work. This definition suggests that when people experience excessive stress, there is a high risk. And this phenomenon also contributes to some bad consequences, such as mental illness, heart and circulatory problems. Stress as strain felt by somebody mentally, physically, emotionally which may cause symptoms as raised blood pressure and depression. Steps in assessing stress using speech include, when an individual speaks in the presence of an actively recording smartphone or smart speaker, an audio signal is captured. Various features of the audio signal (e.g., pitch, jitter, energy, speaking rate, length, and number of pauses) are then extracted and used as inputs to a machine learning algorithm that yields a result. That depicts whether the woman is under stress or not. In this case our voice analyzer can help women by detecting their stress levels using their routine speech without any special intervention.
DATASET
The datasets used in the prediction of stress was RAVDESS dataset. It is not an easy task to find a database that can classify into stressed or unstressed conditions based on different audio clips from the same speaker. In this project we used a multi-modal database for use in stress-related research using audio-visual that is speech and video dataset named as RAVDESS. Since our focus was primarily based on stress detection in women, we further reduced the usage of the database by considering audio clips of only women. The audio clips of men were excluded in our model.
Link : https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
TOOLS
•	Jyputer Notebook
•	Pycharm



TECHNOLOGIES
•	Machine Learning 
		- Convolutional neural network Algorithm
		- Librosa Python Libraries
                       - MFCC’s Co-efficient Extraction

Algorithm:
Step-1: Reading the dataset 
Step-2:Plotting the audio file's waveform and its spectrogram
Step-3:Plotting MFCC
Step-4:Defining label to dataset
Step-5:Data Splitting
Step-6:Analyzing Features of audio files using librosa
Step-7:Data Making/Processing
Step-8:Creating the CNN Model
1.Set up Keras util functions
2.Model Summary
3.Compiling the model
4.Training the model
5.Evaluate loaded model on test data
Step-9:Predicting stress on the test data
Step-10:Actual Values vs Predicted Values



	




