# TrackNetPickleBall

## System Environment
GPU is required for training the model and getting predictions (steps 5 and 6). CPU can be used for everything else.

[Kaggle CPU Docker Image](https://console.cloud.google.com/gcr/images/kaggle-images/GLOBAL/python)

[Kaggle GPU Docker Image](https://console.cloud.google.com/gcr/images/kaggle-gpu-images/GLOBAL/python)

## Quick Overview:
Step 1. Turn video into frames
Step 2. Label frames by hand to get label csv
Step 3. Adjust format of the label csv
Step 4. Use label csv to turn frames into .npy files
Step 5. Train model using .npy files and get new weights
Step 6. Use video and new weights to get prediction csv
Step 7. Use video and prediction csv to show ball trajectory
Step 8. Use prediction csv and label csv to get model performance

For more information about each step, look into its respective folder.

## The Model

This project is an extension of TrackNetV2. 

## Sources
[Labelling Tool](https://github.com/Chang-Chia-Chi/TrackNet-Badminton-Tracking-tensorflow2)

[TrackNetV2](https://nol.cs.nctu.edu.tw:234/open-source/TrackNetv2)
