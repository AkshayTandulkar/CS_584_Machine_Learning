# CS_584_Machine_Learning

ABSTRACT
This solution tackles the problem of detecting human faces from videos. Once the human face is detected, identification of person (name) is accomplished. 
Haar and HOG methods which are used to detect faces have limitations in detecting it correctly. 
Haar cascade classifier gives more false positives. 
HOG has higher accuracy for face detection than Haar cascade classifier, but the limitation is that the human must be within perfect area on the screen. 
To overcome these shortcomings Dlib’s face detection uses HOG + SVM, which makes it easier to use and faster to train. Dlib is far better than Haar cascade classifier over implementation, speed and accuracy. 
So Dlib will be used in this project instead of Haar and HOG. For face recognition part Knn classification will be used.

INTRODUCTION
In this project I seek to address the problem of detecting and recognizing faces from videos. 
This will be helpful in various applications like student class attendance analysis. 
It will be useful in large organizations wherein a large pool of video data exists and needs to be analysed for the person present in that video. 
For example if you want all the videos containing the CEO of your organization and the video file’s name doesn’t have it. 
In this case by extracting the name of the people present in the video, this task can be accomplished. 
The names of the people will be stored in a text file for further analysis.
