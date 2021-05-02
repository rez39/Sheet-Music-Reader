# Project ID: 31
# Project Sheet Music Reader
## Github link: https://github.com/Digital-Image-Processing-IIITH/project-four-avengers
### Team Members: 
- Anuarag Sahu 
- Abhinav Navnit
- Deeksha Devendra
- Rajashekar Reddy Chinthalapani
### Main Goal:
To implement an image processing algorithm that scans in sheet music and plays the music in the sheet. 
### Problem Defination:
The problem is defined as to automate the process of reading sheet music. The potential applications are to ease the tedious process of transposing music notes by hand and also help the musician to manipulate scores with ease.
Moreover it helps musicians to use the sheet music reader as a practice aid to check their own sounds with a digital reference. The end case is to be able to identify the frequency of the given note and also find how time to play the note for and sythesize it using an audio synthesizer.

The Problem has been divided into three main sub tasks, namely:
- Segmentation and Preprocessing (mainly correspons to identifying the frequency of each note)
  - To segment the given sheet of music, into seperate lines of staff lines
  - To remove the staff lines and note the location of each note on the staff line
  - To convert the obtained image devoid of the staff lines into binary image using Otsu's method of automatic image thresholding
- Object detection (mainly corresponds to identifying the time for which it is to be played)
  - Cleff detection
  - Key Note Detection
  - Quarter and Eighth notes detection
  - Whole and Half note detection
  - Dotted notes detection
  - Rest Detection
### Project Milestones and Timeline
Three Milestones : 30 October, 14 November and 18 November
- Tasks to be done by 30 October 
  - Segmentation (by Rajashekar Reddy and Deeksha Devendra)
  - Rest Detection (by Abhinav Navnit)
  - Audio Synthesis (by Anurag Sahu)
- Tasks to be done by 14 Nov
  - Preprocessing (by Rajashekar Reddy and Deeksha Devendra)
  - CLeff, Key Note, Quarter and Eight Note Detection (by Deeksha Devendra and Abhinav Navnit)
  - Whole, Half and Dotted Notes Detection (by Abhinav Navnit and Anurag Sahu)
- Tasks to be done by 18 Nov
  - Final Integration of the Pipeline 
  - Presentation Slides
  - Other required documents
### Dataset
We dont have any model training, so we dont require any training dataset. We would be requiring handwritten sheets of music for testing the algorithm functionality, which is to be obtained from online resorces.



