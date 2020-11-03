# Face morhper


First, 68 facial feature points were detected 
by human face feature detector, and the feature points were 
triangulated. Then affine transformation and triangular 
deformation were performed, and images of different Alpha 
were fused to generate GIF of deformation process.

# Requirement

* opencv
* dlib
* imageio
* scipy
* numpy
* shape_predictor_68_face_landmarks.dat
***
You only download the `.dat`file,click [here](https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat) to download,and change the `.jpg`file to yours picture,
then run the `face_morpher.py` file.
