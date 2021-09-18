# CNN Music Genre Classification

## Description:
 
This project utilizes a Convolutional Neural Network to be able to accurately predict between 10 different music genres from the GTZAN genre collection.

## Environment:

* **Python 3.8.5** using **Anaconda** 

## Required Libraries:

* **numpy 1.19.2**
* **pandas 1.1.3**
* **seaborn 0.11.0**
* **librosa 0.8.0**
* **tensorflow 2.4.1**

## How to test:

* The code will prompt you if you wish to test with 10 genres or 2 genres
	* If the 2-genre option is selected it will give you an additional prompt to choose between: 
		* country vs. jazz 
		* rock vs. classical
* The program will initially output
	* Audio
	* Visualization of the audio as a Waveform, Spectrogram, and Mel Spectrogram
* The program will continue to process the .wav files, split each file into segments, and send that data to the .json file
* The information in the .json file will then be split into training, validation, and testing data to run through the CNN 
* Training should take about 10 mins for all 10 genres (at 100 epochs) and about 5 min for 2 genres (at 100 epochs)
* There are then 5 precoded samples that can be run to see how accurately the CNN predicts the genre

Base code retreived from [here](https://www.kaggle.com/bryanchooo/genre-classification-using-tensorflow-cnn)
GTZAN genre collection retreived from [here](https://www.kaggle.com/bryanchooo/genre-classification-using-tensorflow-cnn/data)
"# MusicGenreCNN" 
"# MusicGenreCNN" 
