# Birdcall Recognition Algorithm

## What?
This repository contains the Jupyter notebook for a birdcall recognition algorithm, based on a ML model.

## Why?
The project was part of my data science training with Digital Futures. I chose this topic because I am interested in the ethical use of data technologies and have prior experience in audio processing. This algorithm could serve the purpose of understanding animal behaviour better and help the protection of the environment.

## Data?
Yes, please. The data came from the [xeno-canto](https://www.xeno-canto.org/) website via kaggle. It contained information about the birdcalls, technical features of the recordings as well as a path to the .mp3 files.

## How?
Building the algorithm, I imported the .mp3 file using the [librosa](https://librosa.org/doc/latest/index.html) library for Python. Then, I created an audio cleaning pipeline and processed the data. Finally, I trained several models of which an SVM proved to be best, so I based the algorithm on this model.

## So?
The algorithm, of course can be improved. My most desired additions would be: 1.) a generator object, so the audio data would not hog all the memory; 2.) an algorithm to dynamically find the threshold where chirps happen; and 3.) an additional layer of noise filter which would enable processing background audio.

## Can I?
See it? [Brace yourself!](https://www.youtube.com/watch?v=vCDruTVTBDM&feature=youtu.be)