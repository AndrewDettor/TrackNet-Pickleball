# Step 6 - Make Predictions
[Example Predictions File](https://drive.google.com/file/d/1o047gPPUavZjDLvJhv94GQVg75PN1kpu/view?usp=sharing) \
Once we have new weights, we can make predictions on a video.

This jupyter notebook takes in a list of videos to predict on and 2 sets of 2 weights to compare performance with.

It outputs a csv file of predictions per video and per set of weights.

NOTE: This requires a GPU.

## Step 6.1
Change 'vids' and 'weight_dirs' variables under "Directories" section. 

NOTE: Keep in mind the different formats of weight files. The old TrackNetV2 weights were stored in a single file, whereas the new trained weights are stored in a directory.

NOTE: This notebook was originally used in a Kaggle cloud computing environment, so you might want to comment out the cell above where these variables are declared.

## Step 6.2
Change the variable 'predict_csv_dir' under the section 
"Run prediction function with old and new weights" to change where the prediction csvs are saved to.

## Step 6.3
Run all cells from start to finish. The notebook should output a csv of predictions per combination of weights and videos.
