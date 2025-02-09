# BirdCLEF

University project for the `2022/23/1 Data Mining and Machine Learning` course, focusing on the Kaggle BirdCLEF competition dataset from 2022, which had the goal of helping researchers understand how changes in the environment affect species living in difficult-to-access, high-elevation habitats by developing bioacoustic monitoring systems.

## Main results:

- Performed EDA on the dataset.
- Processed the audio data and transformed it into **log-scaled Mel Spectrograms**, because birds make sounds in a very tiny interval of the full frequency spectrum.
- Augmented the data in two ways:
  - **Raw Audio Augmentation**: where we transform the signal before transforming it to a spectrogram.
  - **SpecAugmentation**: where we make copies by blocking out parts of a spectrogram.
- Built and trained a **Convolutional Neural Network** to classify the birds in the data.
