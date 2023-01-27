# Face-Detector-using-python
You need to have opencv library installed and also you have to provide the path of the haarcascade file that is used for face detection.

In this code, we first load the cascade classifier using the cv2.CascadeClassifier() method. The classifier is a pre-trained model that can detect faces in images. Then we read an image using the cv2.imread() method and convert it to grayscale using the cv2.cvtColor() method. Then we use the detectMultiScale() method of the classifier to detect faces in the image. Finally, we draw rectangles around the detected faces using the cv2.rectangle() method and display the image using the cv2.imshow() method.
