# BirdCLEF
University project for the `2022/23/1 Data Mining and Machine Learning` course, focusing on the Kaggle BirdCLEF competition dataset from 2022, 
which had the goal of is to help reasearchers understand how changes in the enviroment effect species, that are living difficult-to-access, 
high-elevation habitats by help developing bioacustic monitoring systems.

## Main results:

- Performed EDA on the dataset.
- Processed the audio data and transformed it into __log-scaled Mel Spectrograms__, because birds make sounds in a very tiny interval of the full frequency spectrum.
- Augmented the data in two ways:
-     __Raw Audio Augmnetation__, where we transform the signal before we transform it to a spectogram
-     __SpecAugmentation__, where we make copies by blocking out parts of a spectrogram
- Built and trained a __Convolutional Neural Network__ to classify the birds in the data.
