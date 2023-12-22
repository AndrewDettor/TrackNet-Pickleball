# TrackNetPickleBall
Follow these steps to create a video that tracks the location of a pickleball and obtain metrics on the model's performance.

## Model Architecture

![model architecture](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/tnv2%20architecture%20picture.png)

## Steps

![flow chart](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Flow%20Chart.jpg)

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

There is also a requirements.txt file straight from the Kaggle GPU image, but it may not be easily usable.

### Weights Files
The weights are too big to upload to GitHub (>25MB), so I uploaded them to Google Drive. The old weights are from the 3-in-3-out model in the TrackNetV2 repository. The new weights are from our best model.

[Old Weights](https://drive.google.com/file/d/16ZnOljaxW6zM4bP7TTo1t81gaty7Egts/view?usp=sharing) \
[New Weights](https://drive.google.com/drive/folders/1EGsddY1fgEJ5ITrfF32aPCn6nml2Anzr?usp=sharing)

## Sources
[Labelling Tool](https://github.com/Chang-Chia-Chi/TrackNet-Badminton-Tracking-tensorflow2) \
[TrackNetV2](https://nol.cs.nctu.edu.tw:234/open-source/TrackNetv2)

## Final Presentation

![1](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-01.jpg)
![2](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-02.jpg)
![3](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-03.jpg)
![4](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-04.jpg)
![5](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-05.jpg)
![6](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-06.jpg)
![7](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-07.jpg)
![8](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-08.jpg)
![9](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-09.jpg)
![10](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-10.jpg)
![11](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-11.jpg)
![12](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-12.jpg)
![13](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-13.jpg)
![14](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-14.jpg)
![15](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-15.jpg)
![16](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-16.jpg)
![17](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-17.jpg)
![18](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-18.jpg)
![19](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-19.jpg)
![20](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-20.jpg)
![21](https://github.com/AndrewDettor/TrackNet-Pickleball/blob/main/Presentation/pickleball%20pres-21.jpg)
