# 3Frames_Uniform_detection

There are two .ipynb files attached in this Repo.

# Dataset
The dataset used for training are uniforms of BSF, CRPF, jammu_kashmir_police.
The total number of images used were 294 images with bounding boxes which were split into train, test and valid.
The classes 
0 -> BSF
1 -> CRPF
2- -> jammu_kashmir_police

# 1. 3frames_uniform.ipynb
-> In this script the model used was EfficientNetB0 

# 2. 3Frames_yolov8.ipynb
-> In this script the data was trained with Yolov8m

Due to less number of images the model trained was not upto the mark. I suggest to use YOLOV8m model to use for prediction to get better results.
The predicted images from YOLOV8m were attached to this repo.
