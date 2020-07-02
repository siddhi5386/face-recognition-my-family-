A face recognition model made for my family members.

The step by step process:-

1.The model is first tained to find the encodings for the dataset.

For this initally the faces are detected in an image using face recognition (or using deep learning module dnn or opencv) and dlib library and then the encoding are formed for your own dataset.
(Pretrained encodings are used for faster formation of encodings on your own dataset using face_recognition library)

2. Then after succesfull formation of the encodings, output can be checked! For this first the input image is passed for face detection then the encodings are formed for the face so detected, these encodings are then compared to the encodings made for your dataset(in step 2) and the person with least difference in the encodings(E for the input image and EE from the encodings of the dataset) is recognized.


Note:- This recognition can be done for both on images and realtime.But the speed in recognising on realtime depends on GPU.

IMPORTANT:- The dlib library (used for using the face recognition library) for python 3.5 above is not avilable in compiled form which needs to be done by urself on visual studios!!! But you can use GOOGLE COLLABORATORY!!

BUT on colab the webcam is not supported hence using python version less than 3.5 (Pycharm ide) was the best solution for me.
