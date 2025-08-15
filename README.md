# Cricket Pose Analysis with Mediapipe

This script analyzes cricket batting posture from a local video file or a YouTube URL using [MediaPipe](https://developers.google.com/mediapipe) pose detection.  
It overlays visual cues on the video based on pose metrics such as elbow angle and spine lean.

## Features
- Downloads video from YouTube or uses a local file.
- Detects pose landmarks using Mediapipe.
- Computes biomechanical metrics (e.g., elbow elevation).
- Overlays feedback icons and text directly onto the video.
- Outputs an annotated video.

## Requirements
See `requirements.txt` for the full list.

Install them with:
```bash
pip install -r requirements.txt

