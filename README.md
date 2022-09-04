# Video_Game_DINO_AI

This project is one of the coolest projects. Create your own Video Game AI. 😎

The goal of the project is to create your AI and a using Pytorch, Stable-Baselines3, Pydirectinput, Pytesseract. 😃

## Intallation ⚡

``` !pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu113 ```

``` !pip install stable-baselines3 ```

``` !pip install mss pydirectinput pytesseract ```

## Import Dependencies 🤝

* mss used for screen capture
``` from mss import mss ```

* Sending Commands on Input Keyboard
``` import pydirectinput ```

* Opencv allows us to do frame processing
``` import cv2 ```

* For create a matrix
``` import numpy as np ```

* OCR for Game Over extraction
``` import pytesseract ```

* Visualization of the data frames
``` from matplotlib import pyplot as plt ```

* For allows us to create a break in time
``` import time ```

* Create Environment for the Video Game
``` from gym import Env ```
``` from gym.spaces import Box, Discrete ```
