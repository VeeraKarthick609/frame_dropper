# Video Frame Downsample Script

This Python script utilizes OpenCV to read an input video file, downsample its frames by selecting every 4th frame, and save the result as a new output video file.

## Overview

The script takes an input video file, reads its properties, downsamples the frames by selecting every 4th frame, and saves the result as a new output video file. This downsampling is achieved by adjusting the frames per second (fps) in the output video.

## Prerequisites

- Python 3.x
- OpenCV (cv2)

Install the required packages using:

```bash
pip install opencv-python
