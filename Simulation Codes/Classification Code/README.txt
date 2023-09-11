This is applicable for all classes:

1. Each folder consist of a sentinel-2 images of two different dates. This are .dim files which can be open by SNAP. Also folder consist of 2 .tif files corresponding to each .dim file, this can be also opened by SNAP.

2. There are three .ipynb files which are python files in which the algorithms are written that we used to classify the images to different classes. We used 3 different algorithms namely SVM, Randomforest, DNN.

3. We are running our algorithm pixel by pixel so it is actually classifying each pixels into different classes. The dataset for training our algorithms is extracted by SNAP by making masks on certain areas of the whole image, and the pixels values are then extracted in the text files that are present in the folder. This dataset is converted into .csv files using python and the code for the same is written in each .ipynb files.

4. Finally we are running our algorithm on whole image pixel by pixel using python. The code runs on the .tif files. 

5. Finally the results of each classification from every algorithm is stored in the greyscale images in .png files. This final images are then used for change detection and finding accuracy and confusion matrix.  