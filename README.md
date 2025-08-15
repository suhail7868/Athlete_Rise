Cricket Pose Analysis with MediaPipe
This script analyzes cricket batting posture from a local video file or a YouTube URL using MediaPipe pose detection.
It overlays visual feedback on the video based on pose metrics such as elbow angle and spine lean.

Features
Download video from YouTube or use a local video file.

Pose detection using MediaPipe.

Biomechanical metrics: Computes relevant angles (elbow elevation, spine lean, etc.).

Visual overlays: Draws feedback directly on the video (icons and text).

Annotated output: Saves an annotated video with feedback cues.

Requirements
See requirements.txt for the complete list.
To install dependencies:

bash
pip install -r requirements.txt
Usage
Supply a local video file or YouTube URL as input.

Run the script. It will:

Download the video if a URL is provided.

Run pose detection for each frame.

Compute biomechanical angles.

Draw feedback overlays.

Save the annotated output file.

Output: The result is a video with visible pose landmarks, angle metrics, and feedback graphics.

Assumptions & Limitations
The subject should be fully visible in the frame for accurate pose detection.

Best results with good lighting and a stable camera.

Not optimized for multiple people — may misinterpret group frames.

Hardcoded angle thresholds: Not tuned for all cricket styles.

Real-time speed depends on device performance.

About MediaPipe
Uses the latest MediaPipe Pose detection.

Fully open-source and cross-platform.

Can be customized via MediaPipe Model Maker if needed.

For more info: see the MediaPipe Solutions Guide.
