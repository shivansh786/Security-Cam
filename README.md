    This project is based on FRAME SUBTRACTION APPROACH in A.I using python 

A Movement recognition system is a
Technology capable of matching a
Movement from a digital image
Or a video frame against a database
Of faces, typically employed to authenticate 
 Users through ID verification services,
Works by pinpointing and measuring
Facial features from a given image

Algorithm Used --
We have 2 images:-
currentFrame – A grayscale image of the current frame 
of the scene,
previousFrame – A grayscale image of the previous frame 
of the scene, and
threshold – The threshold that determine whether the 
movement is motion or not.
1:- Calculate the Difference between the currentFrame
and previousFrame
2:- Using the threshold value as a Threshold for the image 
calculated in (1), we calculate the areas which have 
changed in the currentFrame from the previousFrame.
3:-  Resulting image from (2) is then highlighted in the
currentFrame to indicate areas of motion.
The above algorithm forms a basis of background 
subtraction method. We modify the above algorithm for 
space and time to achieve a more complex but efficient 
motion detection algorithm

At last i hope you enjoyed this!!!
