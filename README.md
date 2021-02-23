# Facial-recognition-and-Mask-Identification
This project was designed to take in an image, and apply bounding boxes around any recognized faces. Those bounding boxed images were then cropped and fed into a CNN I trained to identify whether the person or people in the image are wearing a mask or not.

The facial recognition utilizes CV2 library to identify bounding boxes.
The Convolution Neural Network uses pre-trained ImageNet weights, with an additional flatten, dense and output layer added for weight training.

The final output is the same image, with bounding boxes around the faces that are green if the individual is wearing a mask, or red if the individual is not wearing a mask.

I first tested this notebook using my webcam on my laptop:

![](Output/Test_image%20me.png)
