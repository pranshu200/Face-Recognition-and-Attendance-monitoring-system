# Face-Recognition-and-Attendance-monitoring-system
To recognize people collectively in real time using webcam , implemented using Python and OpenCV and mark the attendance by storing in a csv file with time and date.

# Languages or Frameworks Used
<ul><li>Python: language</li>
<li>NumPy: library for numerical calculations</li>
<li>Opencv : cv2 for accessing camera</li>
<li>face_recognition: for face recognition</li>
</ul>

# Project Link:
Link: https://github.com/pranshu200/Face-Recognition-and-Attendance-monitoring-system.git

# Approach:
1. Look at a picture and find all the faces in it.<br>
2. Focus on each face and understand that even if a face is turned in a different direction or in bad lighting, it is still the same person.<br>
3. Pick out unique features of the face that you can use to tell it apart from other people— like how big the eyes are, how long the face is, etc.<br>
4. Compare the unique features of that face to all the people you already know to determine the person’s name.<br>

# Techniques used:
1. HOG (Histogram of Oriented Gradients) algorithm for finding faces.<br>
2. Generate Facial landmarks for faces posing and projected at different angles.<br>
3. 128 different measurements of a image generated. using these measurements we can define a person, and differentiate between people as well.<br>
4. Last step to differentiate them and get names (used linear SVM classifier.)<br>
