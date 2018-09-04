# Arduino-Face-Tracking
Final project for CS-290M

This project was in collaboration with Spencer Rendano, and served as our final project for CICS-290M.

From the Processing side, the OpenCV API is used to read in (X,Y) coordinates of a person's face (which uses Harr Cascade Classifiers).

From the Arduino side, the coordinates are read in through a byte buffer. From here, we determine how to move the camera so that these coordinates fall within the center of the Logitech camera's capture.
