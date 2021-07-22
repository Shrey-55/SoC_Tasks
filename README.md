# SoC_Tasks
Tasks done: A1, A2, B3, B4, C1, D5, D6, D7, D9
Total Credits=120

### Task1(A1) Pandas Introduction
Introductory exercise of pandas. Learnt about import a csv file and different ways of extracting the information needed from the data.
### Task2(A2) Matplotlib Introduction
Introductory exercise of matplotlib. Used along with python to plot different types of graph for the data provided.


### Task4(B3) Age and Gender Detection
Used a pre-trained Caffe model to make an Age and Gender detection project. For this project a youtube tutorial-https://www.youtube.com/watch?v=rZTHD-kewt8 was referred. 

Source code : In the source code, the pre-trained models are loaded and used diretly. The code makes the bounding box and writes down the age range and gender on it if a face is detected.

My code: After getting incorrect range predictions, I had a look at the prediction output from the model and I found that sometimes it predicted 2 ranges with almost equal confidence, but since the one with higher value was taken, the second range was completely ingnored although this was the correct range in some cases. To get over this, instead of a using just the range with maximum value, I took the weighted average over all ranges to get a better prediction.

Models used for the code can be found in "Extras" folder.

### Task5(B4) Age and Gender Detection on youtube videos
The same  models as used in Task4 are now used on youtube videos.
Code: To take videos from youtube and also output directly to the drive, some libraries are added first. Also since this code was written on Google colab, appropriate patches are added. 
After all the initialisations, the models are loaded and just like the previous code, they are processed and an output file is sent to the drive. Here are some results.

Input file: https://www.youtube.com/watch?v=Xygk7UjKM2g

Output file:https://drive.google.com/file/d/1Izj70VY_30Ttyv0ambl7-5QkRKo79y8J/view?usp=sharing

### Task6(C1) Facial detection app
Facial detection app , with age and gender predictions is made. A zip file to the android studio project is attached here. The app is made using Tensorflow Lite on android studio.

## Other CV projects:

### Gesture Volume control(D5):
Handtracking module is used to detect hand and control volume with respect to tha distance between tip of thumb and tip of index finger.

### AI virtual mouse(D6):
Again the handtracking module is used to make a mouse with different gestures of the hand. I have added feature to move (when 1 finger up), stop (when 2 fingers up), click ( when index and middle up and close), scroll up( fist) , scroll down( all fingers up)

### Finger counting(D7):
Here too, the handtracking module is used and number of fingers are counted by comparing the co-ordinates of tip and base of finger.

The handtracking module is added in "Extras"

### Facial detection(D9):
Here, a facial recognition module is used to detect the face. This module is again written by me with help of youtube tutorials. Mediapipe is used


