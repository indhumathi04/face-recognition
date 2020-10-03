# **FACE RECOGNITION USING OPENCV** 
 Here in the face recognition project which i have attached, contains 2 files one for capturing samples for which the recognizer is to be trained and another one for training and identifying faces. 
 
## **capturing samples**
 Here we use pretrained XML classifier **haarcascade_fronalface_dafault.xml** available in opencv to detect the human face. Specify unqiue ID for each person. Then the detected part is captured and stored in a separate file. The images are captured as per the maximum count specified (here 30).
## **Training and recognition**
 Here we load the images from the saved folder and the associated ID's of the images and train the images using LBPH face recognizer algoithm. Then start the video capture to open the camera and use haarcascade classifer to detect face and pass it to the trained LBPH algorithm to identify the particular person.
 
