# Step 2: Labelling Tool
[Example Labels File](https://drive.google.com/file/d/198jLZ56IMKi0wlC45YRw_Suvx_nklPa9/view?usp=sharing) \
This is a GUI that helps label the ball location in video footage. It outputs results as a .csv file.

## Step 2.1
Replace default='test/test.mp4' in '--label_video_path' argument in parser.py with video you want to label (line 44).

## Step 2.2
If you want to continue labelling a video where you left off, replace default='' in '--csv_path' argument in parser.py with the location of the label csv (line 46).

## Step 2.3
Run python3 labelling_tool.py. This outputs a csv of labels.
