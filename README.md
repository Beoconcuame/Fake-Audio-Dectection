# FakeAudioDetection
Machine learning classification for Fake Audio Detection


## **** Annotation ****

Regarding the data files:

frame_length_data: Contains data after preprocessing with n_mfcc = 68 for each frame length.

processed: Used to store preprocessed data in the form of MFCC features, saved as JSON.

result_chart: Contains average data (accuracy, f1-macro, precision, recall) after 10 rounds of Stratified K-fold splitting (Used for chart visualization).

result_frame: Contains average accuracy data of models based on frame length (Used for chart visualization).

compare: Compares two audio files (fake and real) with the same source for Exploratory Data Analysis (EDA).

Compilation of data file links: (Please email me at 22520675@gm.uit.edu.vn to request access).

image results: Contains images that will be used in the report.

removing silence: Script for removing silence from audio.

signal EDA: File for EDA analysis of audio.

modelin_analysis: Runs the model and plots charts.

Preprocessing experiment and tuning: Used for experimenting with preprocessing techniques and tuning the model.
