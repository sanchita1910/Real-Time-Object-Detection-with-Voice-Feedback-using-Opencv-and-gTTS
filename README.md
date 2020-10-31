# Real-Time-Object-Detection-with-Voice-Feedback-using-Opencv-and-gTTS
Human Computer Interaction project- Real Time Object Detection with Voice Feedback using Opencv and gTTS

Here Object detection is done using You Only Look Once (YOLO) approach.  In YOLO ,the algorithm looks the image completely by predicting the bounding boxes using convolutional network and finds class probabilities for these boxes and also detects the image faster as compared to other algorithms.   this algorithm  has been used for detecting different types of objects and have created a software which would return voice feedback to the user. The model is trained with the Common Objects In Context (COCO) dataset. YOLO algo been utilized to make a navigation assistant which tells what is the object that is in front of the camera .The entire system had two modules:
For Object Detection: The YOLO model detects the object in search. It has been modified to tell  the object which is present near the camera.
and for Text to Speech: Pyttsx library of python was used to give back the output in the form of speech. For more informaation refer - https://towardsdatascience.com/object-detection-with-voice-feedback-yolo-v3-gtts-6ec732dca91
