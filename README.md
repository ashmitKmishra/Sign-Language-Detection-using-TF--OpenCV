# Sign-Detection--TensorFlow
 This code sets up an object detection model using TensorFlow's Object Detection API to detect objects in a live video stream from a webcam. Here's a summary of what the code does:  
 1). Defines paths and configurations for the object detection model, including paths for annotations, images, models, and pretrained models. 
 2). Generates a label map file (label_map.pbtxt) for the two classes ('Mask' and 'NoMask').
 3). Converts the image dataset into TFRecord format for training and testing.
 4). Configures the object detection pipeline. Loads the detection model and restores the checkpoint. Sets up the webcam feed for object detection. 
 5). Detects objects in each frame of the webcam feed and displays the results in real-time using OpenCV. 
 Overall, this code sets up and runs an object detection model to detect whether people in the video stream are wearing masks or not.
