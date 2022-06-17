# Pose Detection Project
Final project to Machine Learning 1 course at ITI 9-Month Diploma track AI-Pro

Demo Video:
https://drive.google.com/file/d/17meu0nuc3DFz7fWtH73BTOZX0GrJxg5i/view?usp=sharing

### Technology Used
- Using OpenCV to deal with images and open video stream from camera
- Using Mediapipe to get face landmarks
- Using Pandas and Numpy
- Using scikit-learn to preproccess and train model
- I used LinearSVR model to train this data with great accuracy

### Project Steps
- Getting Face landmarks by Mediapipe and create features dataset
- Cropping Images to create another dataset with just a face
- Craeting labels dataset from mat files to be Pitch, Yaw and Roll
- Preproccess the data by using PCA and Standardization
- Using MultiOutputRegressor and LinearSVR Model and train the model
- Testing the model in random images then testing it by live camera


