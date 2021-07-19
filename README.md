# SoC_Tasks


### Task1(A1) Pandas Introduction
Introductory exercise of pandas. Learnt about import a csv file and different ways of extracting the information needed from the data.
### Task2(A2) Matplotlib Introduction
Introductory exercise of matplotlib. Used along with python to plot different types of graph for the data provided.
### Task3b(B2) Seaborn Introduction

### Task4(B3) Age and Gender Detection
Used a pre-trained Caffe model to make an Age and Gender detection project. For this project a youtube tutorial-https://www.youtube.com/watch?v=rZTHD-kewt8 was referred. 
Source code : In the source code, the pre-trained models are loaded and used diretly. The code makes the bounding box and writes down the age range and gender on it if a face is detected.
My code: After getting incorrect range predictions, I had a look at the prediction output from the model and I found that sometimes it predicted 2 ranges with almost equal confidence, but since the one with higher value was taken, the second range was completely ingnored although this was the correct range in some cases. To get over this, instead of a using just the range with maximum value, I took the weighted average over all ranges to get a better prediction.

Models used for the code can be found in "Extras" folder.

### Task5(B4) Age and Gender Detection on youtube videos
### Task1(A1)
### Task1(A1)
### Task1(A1)
### Task1(A1)
### Task1(A1)
