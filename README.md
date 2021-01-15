# Emoji-Creation-with-Deep-Learning
## About
Trained a Keras model for recognizing facial expressions using the FER2013 dataset and predicted the emotions. Then, mapped emojis with different facial expressions and displayed 
the relevant emoji after prediction in a GUI using OpenCV.

## The Dataset
The FER2013 dataset ( facial expression recognition) consists of 48*48 pixel grayscale face images. The images are centered and occupy an equal amount of space. The dataset consist of facial emotions of following categories:

• 0:angry
• 1:disgust
• 2:feat
• 3:happy
• 4:sad
• 5:surprise
• 6:natural

The dataset is stored in the "Data" folder with seperate train and test directories

## Steps
1.) Built a convolution neural network architecture and train the model on FER2013 dataset for Emotion recognition from images. (File name - Train.py)

2.) Created a folder named emojis and saved the emojis corresponding to each of the seven emotions in the dataset.

3.) Written a code to analyze the live video feeds in real-time to capture the face and find out the expression. And then, classified the expression 
and mapped it to the corresponding emoji or avatar. (File name - gui.py)
