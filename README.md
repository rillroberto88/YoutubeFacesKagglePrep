# YoutubeFacesKagglePrep
Preparing the YouTube Faces dataset available on Kaggle for training

A preprocessed version of the YouTube Faces dataset is available on Kaggle: https://www.kaggle.com/selfishgene/youtube-faces-with-facial-keypoints#youtube_faces_with_keypoints_large.csv

It contains videos of celebrities annotated with face detections and facial landmark points. The dataset is further processed with using Python in a Jupyter Notebook:

1. Save all the images as PNG files, together with the corresponding face bounding boxes and landmarks.

2. Resize the images to a predefined size, and modify the annotations accordingly.

3. Split the data into train, validation and test sets.
