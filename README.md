# TrackNetPickleBall

## Quick Overview
Step 1 - Turn video into frames \
Step 2 - Label frames by hand to get label csv \
Step 3 - Adjust format of the label csv \
Step 4 - Use label csv to turn frames into .npy files \
Step 5 - Train model using .npy files and get new weights \
Step 6 - Use video and new weights to get prediction csv \
Step 7 - Use video and prediction csv to show ball trajectory \
Step 8 - Use prediction csv and label csv to get model performance

For more information about each step, look into its respective folder.

## System Environment
GPU is required for training the model and getting predictions (steps 5 and 6). CPU can be used for everything else.

[Kaggle CPU Docker Image](https://console.cloud.google.com/gcr/images/kaggle-images/GLOBAL/python) \
[Kaggle GPU Docker Image](https://console.cloud.google.com/gcr/images/kaggle-gpu-images/GLOBAL/python)

### Weights Files
The weights are too big to upload to GitHub (>25MB), so I uploaded them to Google Drive. The old weights are from the 3-in-3-out model in the TrackNetV2 repository. The new weights are from our best model.

[Old Weights](https://drive.google.com/file/d/16ZnOljaxW6zM4bP7TTo1t81gaty7Egts/view?usp=sharing) \
[New Weights](https://drive.google.com/drive/folders/1EGsddY1fgEJ5ITrfF32aPCn6nml2Anzr?usp=sharing)

## Data Files
[Example Raw Video](https://drive.google.com/file/d/1_IttM4H7DOy-TL_xemQOnQhvGvwnt7TG/view?usp=sharing) \
[Example Labels File](https://drive.google.com/file/d/198jLZ56IMKi0wlC45YRw_Suvx_nklPa9/view?usp=sharing) \
[Example .npy Files](https://drive.google.com/drive/folders/1Qj6EqrBuW5BgGxX16rYnZd9RH5YGGSTN?usp=sharing) \
[Example Ball Trajectory Video](https://drive.google.com/file/d/1t3KB5M0vt2GyOXPKkXG0Gr7wnQNK5sFI/view?usp=sharing)

## Sources
[Labelling Tool](https://github.com/Chang-Chia-Chi/TrackNet-Badminton-Tracking-tensorflow2) \
[TrackNetV2](https://nol.cs.nctu.edu.tw:234/open-source/TrackNetv2)
