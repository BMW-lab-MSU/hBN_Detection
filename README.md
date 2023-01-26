# hBN_Detection
In this work, we have implemented a new deep learning pipeline to classify crystallites of hBN based on coarse thickness classifications in reflected-light optical micrographs. We have used
DetectorRS as the object detector and trained it on 177 images containing hexagonal boron nitride (hBN) flakes of varying thickness. The trained model achieved a high detection accuracy for the rare category of thin flakes (< 50 atomic layers thick). Further analysis shows that our proposed pipeline could be generalized to various
microscope settings and is robust against changes in color or substrate background. For training on 2D material images, we chose DetectoRS algorithm with Cascade+ResNet-50 as the backbone detector architecture implemented in MMDetection library.
