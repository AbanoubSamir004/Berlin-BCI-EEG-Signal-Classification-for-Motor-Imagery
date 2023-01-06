# Berlin-BCI-EEG-Signal-Classification-for-Motor-Imagery
Overview:

This project involved the development of machine learning models to classify between right hand and left hand movement based on EEG signals. The data for the project was provided in the form of 7 Matlab files, each corresponding to a different person, and contained continuous EEG signals, target cue information, and additional information such as channel labels and sampling rate. To improve the performance of the models, the data was pre-processed using techniques such as power spectral density (PSD) analysis and bandpass filtering to identify and isolate the most relevant frequencies. The goal of the project was to build a model that could accurately classify motor imagery for each person using a cross-validation technique with k=5, and to compare the performance of the models with and without the use of filtering.

Key responsibilities:

•	Developed machine learning models to classify motor imagery based on EEG signals

•	Applied PSD analysis and bandpass filtering to the data to identify and isolate relevant frequencies

•	Used a cross-validation technique with k=5 to the calibration data

•	Compared the performance of the models with and without filtering

•	Provided 7 accuracies, one for each person

Results:

The project resulted in the development of machine learning models that were able to accurately classify motor imagery for each person based on the EEG signals. The use of PSD analysis and bandpass filtering improved the performance of the models, as demonstrated by higher accuracy score on the test set.

## Before Filtering
![Screenshot 2023-01-06 212330](https://user-images.githubusercontent.com/60902991/211084657-56a15db4-c75b-467b-8c7b-ee37c26478b5.png)

## After Filtering
![Screenshot 2023-01-06 212315](https://user-images.githubusercontent.com/60902991/211084661-0eb1c730-37b0-4907-8cd4-cf280cd2f7d7.png)

## Accuracy Score
![Screenshot 2023-01-06 212804](https://user-images.githubusercontent.com/60902991/211085307-2eec6927-6c17-4ff0-bc53-c05904e47411.png)


Skills demonstrated:

• Machine learning

• EEG signal processing

• PSD analysis

• Bandpass filtering

• Cross-validation
