# Autonomous Bot using CNN
CNN stands for Convolutional Nueral Network which was developed using Machine learning techniques. YOLO is the frame work used to develop the CNN . Using this model we can identify each room number in the floor using object_detection technique. This model can be testined real-time using live camera streaming  or from pre-recorded video. Here we use supervised machine learning approach where we prepare the dataset manually and train the model using Yolov3. We got excellent test accuraqcy ranging from 80 to 90 % in 3000 training steps.

Using this model we simulate a video showing rooms in a hotel which can be seein in the output folder (saved as  test video.gif) inside YOLO_object_detection_model. We testr videos using 'yolo_video.py' and images using 'yolo.py' . The dataset for training the model is available in Dataset.zip . You can test our model by running the respective python file. In order to run our model  successfuly you require  yolov3.weights file which is available in the link: https://drive.google.com/open?id=1-1hOc9NTJWcVFpxZeviUGOgpPtcRFft-.
You can get it from there and paste to the yolo-coco folder. The tested resutls are put in the output folder. It include both video and image output.

We aslo develop a GPS tracking app which can track multiple loaction by activating the GPS. The app is available in the GPS traking floder.Using this app we can enable traking of different rooms in each floor.


![Test Video](https://user-images.githubusercontent.com/62890575/83963162-7ac35e80-a8c1-11ea-929f-b1efebe3754b.gif)
