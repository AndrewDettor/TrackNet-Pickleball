# Step 7 - Get Model Performance
Once we have a csv of predictions and a csv of labels, we can get the performance of the model. 

Since this is a classification model, performance metrics are True Positives, False Positives, False Negatives, True Negatives, Accuracy, Precision, and Recall.

This jupyter notebook takes in a list of videos, their labels, and their predictions and outputs the model's performance on subsets of the video frames.

NOTE: We scale the tolerance for prediction error automatically based on the dimensions of the input video.

NOTE: This does NOT require a GPU.

## Step 7.1
Put videos, their labels, and their predictions under a directory with the same name of the video, excluding the file extension. (e.g. put pickleball.mp4, labels.csv, and predictions.csv in a folder called pickleball).

## Step 7.2
Change the 'vids' variable under the section "Get performance metrics".

## Step 7.3
Change the 'frame_ranges' variable under the section "Get performance metrics".

These allow you to get performance on a specific subset of frames. If you want the entire video, its frame range should be (None, None).

## Step 7.4
Change where the performance dataframe saves to in the last line of the last code cell. (i.e. replace "three_vids_old_and_new_weights_metrics.csv" with where you want to save)

## Step 7.5
Run all cells from start to finish.