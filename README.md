# Audio-Classification

## Overview
Audio classification model based on deep learning in which our goal is to address the problem of classifying the type of urban sound from labeled urban sounds belonging to 10 different classes during model training. I have extracted the features from the audio files using the librosa library and implemented a deep neural network for the classification.




## Dataset
The UrbanSound8k dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. 8732 audio files of urban sounds in WAV format.
The UrbanSound8k dataset used for model training, can be downloaded from the following link.
 https://urbansounddataset.weebly.com/download-urbansound8k.html
 
## Requirement Installation
The Code is written in Python 3.6. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Neural Network Implementation
A simple Neural Network with dropouts was used.
The following results are obtained -

Train accuracy: 95%
Test accuracy: 93%

