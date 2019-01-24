# Multi-Cam-Monitoring-System
Motion activated multi-camera monitoring system for gigE cameras.

Active cameras are constantly checking for motion. When motion is detected, a video file is created for that camera and begins recording. Each recorded frame is overlayed with the current time-stamp. When motion stops being detected for a period of 10 seconds, the camera stops recording and the video is saved to a given directory with a timestamp.
