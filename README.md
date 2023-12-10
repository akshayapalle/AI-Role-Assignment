# AI-Role-Assignment

Creating a program using Computer Vision to track the movement of the balls of different colors across various quadrants in the video provided. 
https://drive.google.com/file/d/1goI3aHVE29Gko9lpTzgi_g3CZZPjJq8w/view?usp=sharing

The program will record the event of each ball entering and exiting each numbered quadrant.
The event data will be recorded in the below format.

Time, Quadrant Number, Ball Colour, Type (Entry or Exit)
Timestamp: consider start of the video as 0 seconds and compute timestamp based on video duration.
The program should have provisions for feeding a new video and output should be saved in the local hard disk. 
Details of which need to be shared at the time of submission.

The processed video will incorporate the following.
1) Ball tracking with color
2) Overlay text “Entry or Exit” & time stamp at the time of entry/exit of a numbered quadrant
3) Text file with records in the format provided above (Time, Quadrant Number, Ball Colour, Event Type (Entry or Exit))
