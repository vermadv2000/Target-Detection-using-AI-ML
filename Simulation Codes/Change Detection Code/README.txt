This is applicble for all classes.

1. The classification result images from each algorithm for two different dates is present as .png files. 

2. Firstly the change is detected between 2 different date images using python code that is written in the "Difference1.ipynb" file. The code takes 2 images as input and generate a differnce image that is stored in the folders for each algorithm.

3. A ground truth rgb image for each class is present in the folder with name "AOI class_name" and consist of the the area of interest and the mask area which is the actual area that is changed between two dates. This masked area is then converted into greyscale image which will be further used to calculate accuracy and confusion matrix.

4. Now we calculate accuracy and confusion matrix for each algorithm by using the change image and ground truth image using the python code written in "Difference.ipynb" file. Also a greyscale image is generated for this differnce with name "algo-name_diff_final_class-name".

5. The results for all are stored in the previous folder with name "Accuracy and Confusion matrix Results".