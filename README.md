# hBN_Detection
In this work, we have implemented a new deep learning pipeline to classify crystallites of hBN based on coarse thickness classifications in reflected-light optical micrographs. We have used
DetectorRS as the object detector and trained it on 177 images containing hexagonal boron nitride (hBN) flakes of varying thickness. The trained model achieved a high detection accuracy for the rare category of thin flakes (< 50 atomic layers thick). Further analysis shows that our proposed pipeline could be generalized to various
microscope settings and is robust against changes in color or substrate background. For training on 2D material images, we chose DetectoRS algorithm with Cascade+ResNet-50 as the backbone detector architecture implemented in MMDetection library.

This code was developed in association with following journal paper: 
"Automatic detection of multilayer hexagonal boron nitride in optical images using deep learning-based computer vision" with DOI 10.1038/s41598-023-28664-3. If you use this code or the data, please cite the journal paper.

The weights for the model described in the publication can be found at https://doi.org/10.5281/zenodo.7779272.
