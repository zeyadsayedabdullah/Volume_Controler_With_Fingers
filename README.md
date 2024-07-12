# Volume Controller With Fingers

This project uses computer vision to control system volume based on hand gestures. It leverages the MediaPipe library for hand tracking and interacts with system audio using the `pycaw` library.

## Files

### 1. `HandTrackingModule.py`

This Python file contains a class `handDetector` that uses MediaPipe to detect and track hand landmarks. It provides functions to find hands in an image and to find the positions of specific landmarks on the detected hands.

### 2. `VolumeHandControl.ipynb`

This Jupyter Notebook demonstrates how to use the `HandTrackingModule` to control system volume based on finger positions:

- **Dependencies:** Requires OpenCV (`cv2`), MediaPipe (`mediapipe`), `numpy`, `pycaw`, and standard Python libraries.
- **Usage:** The notebook initializes a video capture and sets up hand detection. It calculates the distance between thumb and index finger tips to adjust system volume accordingly. Visual feedback of volume percentage and control bar is displayed on the screen.

## How to Use

1. **Setup:**
   - Ensure all dependencies are installed (`cv2`, `mediapipe`, `numpy`, `pycaw`).
   - Clone the repository.

2. **Run the Volume Control Script:**
   - Execute `VolumeHandControl.ipynb` in a Jupyter environment or as a Python script.
   - Adjust your hand in front of the camera to change system volume by moving your thumb and index finger closer or further apart.

3. **Control:**
   - Move your thumb and index finger closer to decrease volume or further apart to increase volume.
   - Visual feedback on the screen shows the current volume percentage and control bar.

## End

- **LinkedIn:** [https://www.linkedin.com/in/zeyadsayed/]
- **Kaggle:** [https://www.kaggle.com/zeyadsayedadbullah]
- **Video Of the project Working From LinkedIn:** [https://www.linkedin.com/feed/update/urn:li:activity:7162226021688188928?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7162226021688188928%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29&originTrackingId=plSDadB9TW2G9%2BuglQ6Dfg%3D%3D&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BQ%2BlN%2BqhESVWVE2XKJuxtyA%3D%3D]
