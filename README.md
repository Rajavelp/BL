# BL

Project Details:

Description: Predict body language of a person based on the set of video frames captured.
Input: Video of a single person
Output: Body language score

Steps:
1. It detects single human being using YOLO3 object detection algorithm.
2. It results body language score based on the gestures.

File deails:
It contains two python files od2new.py and obcord.py.
od2new.py detects human being and written human detected video and its details in csv.
od2new.py takes human detected video file details in csv format and computes body language score.
