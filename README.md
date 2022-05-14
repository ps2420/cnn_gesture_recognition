# Gesture Recognition (Deep learning: CNN/RNN/LSTM/GPU)

## Problem Statement
A home electronics company which manufactures state of the art smart televisions, wants to develop a cool feature in the smart-TV. That can recognise five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

- Thumbs up:  Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds  
- Stop: Pause the movie

## Table of Contents
* [General Info](#general-information)
* [Experiments](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Dataset contains a number of videos, where each video is a sequence of 30 frames (or images). Our aim is to analyze the dataset and build a deep learning model that can identify these gestures

## Conclusions
 - A number of experiments were conducted with different image sizes (120x120, 150x150) with varying combinations of batch sizes (30, 40, 50), epochs (25,50) to train the model. As part of the exercise Conv3D architecture, LSTM, GPU and conv2D architecture was used. Outcomes are listed below:
 - Conv3d architecture
 - LSTM architecture
 - GPU atchitecture 
 
 Where Conv3d architecture seems to perform better compared to LSTM & GPU. Going forward different number of layers and architectures can be tried out to get the better output.

## Technologies Used
- Tensorflow, Keras, Python, and basic python machine learning modules.
- Expermient was conducted on jarvislabs.ai
 
## Acknowledgements
Give credit here.
- This project was inspired by upgrad online learning community https://www.upgrad.com/
- This project was based on linear regressioin module.

## Contact
Created by [@ps2420] - feel free to contact me!
