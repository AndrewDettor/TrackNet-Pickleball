# Step 4 - Create Batches of Data
[Example .npy Files](https://drive.google.com/drive/folders/1Qj6EqrBuW5BgGxX16rYnZd9RH5YGGSTN?usp=sharing) \
The model expects .npy (numpy) files as input. This script takes a video and its labels and generates batches of frames and their labels in .npy format. 
We recommend using a batch size of 250.

The model follows a 3-in-3-out format. Each X is 3 consecutive frames from the video. Each y is those frames' respective heatmaps.

# Step 4.1:
Run python3 gen_data.py --batch=\<batchSize\> --label=\<csvFile\> --frameDir=\<frameDirectory\> --dataDir=\<npyDataDirectory\> (e.g. "python3 gen_data.py --batch=250 --label=new_label.csv --frameDir=framesFolder --dataDir=npyFiles")
