# Introduction to Deep Learning
<p>Hand gesture recognition for disabled individuals using image processing and AI functionalities, with a model utilizing TensorFlow, OpenCV, and MediaPipe libraries.</p>

**Attention:** *This version has been outdated and operating unstably since July 20, 2023.*

## Installations
### Install package
- TensorFlow: <https://www.tensorflow.org/?hl=en>
- OpenCV: <https://opencv.org/>
- Keras: <https://keras.io/>
- Mediapipe: <https://developers.google.com/mediapipe>
- CVzone: <https://www.computervision.zone/>
### Install with pip
```bash
pip install tensorflow
pip install Opencv-python
pip install Keras --upgrade
pip install mediapipe
pip install cvzone
```

## Training the model for the algorithm
Importing libraries for the project
```python
import tensorflow as tf
import numpy as np
import cv2
import os
import random
from tensorflow import keras
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D,MaxPooling2D,Flatten,Dense,Activation
```
## Images of sign language for the disabled
<div align=center>
  <img width="381" alt="image" src="https://github.com/huydaker/SignLanguage/assets/92807267/d613be93-315b-4073-8fb4-78a7374d7b81">

</div>
