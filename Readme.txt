Unzip Training Images.zip so that a folder named "Training images" is created which contains all of the image files.  

Display image.ipynb
Specify folder at top of program for stage_1_detailed_class_info.csv.  Assumes this folder also contains a folder "Training images" with all training image files


CNN model fitting and evaluation.ipynb
Specify folder at top of program which contains a subfolder named "pid lists" with the patient list .npy files and also contains a subfolder named "Training Images", which can be created by unzipping "Traini


Define training, validation, and test patients.ipynb
This file reads in stage_1_detailed_class_info.csv from specified folder and writes:

train_pids.npy
val_pids.npy
test_pids.npy

These files are provided so this program doesn't need to be re-run.