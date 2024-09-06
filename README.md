This is a bit of the ReadMe contents of the original paper repository:
## Overview
Recognizing music genre is a challenging task in the area of music information retrieval. Two approaches are studied here:
1. Spectrogram based end-to-end image classification using a CNN (VGG-16)
2. Feature Engineering Approach using Logistic Regression, SVMs, Random Forest and eXtreme Gradient Boosting.

For a detailed description about the project, please refer to [Music Genre Classification using Machine Learning Techniques](https://arxiv.org/abs/1804.01149), published on [arXiv](https://arxiv.org/).

## Datasets
The *Audio Set* data [released by Google](https://research.google.com/audioset/download.html) is used in this study. Specifically, only the wav files that correspond to the following class labels are extracted from YouTube based on the video link, start and end times. 


## Requirements
- tensorflow-gpu==1.3.0
- Keras==2.0.8
- numpy==1.12.1
- pandas==0.22.0
- youtube-dl==2018.2.4
- scipy==0.19.0
- librosa==0.5.1
- tqdm==4.19.1
- scipy==0.19.0
- Pillow==4.1.1

__Note__: If you encounter any problem in installing the modules you just need to go to python unofficial binnaries and according to your python version you can install them.
