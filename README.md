# **Hand Gesture Recognition with MediaPipe**

The project utilizes MediaPipe's robust hand-tracking capabilities to detect and classify various hand gestures in real-time. This can be used in a variety of applications such as virtual controls, sign language recognition, and interactive gaming.

The hand landmark model bundle detects the keypoint localization of 21 hand-knuckle coordinates within the detected hand regions. The model was trained on approximately 30K real-world images, as well as several rendered synthetic hand models imposed over various backgrounds. See the definition of the 21 landmarks below:
![image](https://github.com/user-attachments/assets/80113028-47a6-4b1e-9bf5-54414f932da0)
The hand landmarker model bundle contains palm detection model and hand landmarks detection model. Palm detection model localizes the region of hands from the whole input image, and the hand landmarks detection model finds the landmarks on the cropped hand image defined by the palm detection model.

## Features:
1. Real-time Hand Tracking: Leverages MediaPipe's efficient and accurate hand-tracking framework.
2. Gesture Classification: Recognizes and classifies a set of predefined hand gestures.
3. Easy Integration: Simple and flexible codebase, easy to integrate into larger projects.
4. Cross-Platform: Runs on multiple platforms, including Windows, MacOS, and Linux.

Requirement:
Use python 3.7
