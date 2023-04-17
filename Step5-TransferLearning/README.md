# Step 5 - Train Weights Using Transfer Learning
TrackNetV2 comes with pre-trained weights from Badminton footage. This jupyter notebook allows one to further train the model using new data from Pickleball footage. NOTE: This requires a GPU.

We allow further training on the last k convolutional layers of the model and freeze training on the rest.

"TNV2_old_weights" are the from the TrackNetV2 repository. We use those as a baseline to further optimize.

## Step 5.1
Change the load_weights, save_weights, and dataDir variables under the section "Reading in Data". 

load_weights is the path to the baseline weights. save_weights is the path where you want to save the new weights. dataDir is the folder with the .npy files. 

NOTE: This notebook was originally used in a Kaggle cloud computing environment, so you might want to comment out the cell above where these variables are declared.

## Step 5.2
Change 'epochs' and 'lr' variables under the section "Model Training Hyperparameters". We recommend training with lr=0.01 and 5 epochs as a start.

## Step 5.3
Change the 'k' variable under the section "Option 2: Freeze everything except the last k conv layers". k is the number of convolutional layers to train further, starting from the last layer of the model. Our final model used k=14.

## Step 5.4
Run all cells from start to finish. The notebook should output graphs of performance and a csv of performance on the train and validation sets. (We use a 70%/30% train/validation split)