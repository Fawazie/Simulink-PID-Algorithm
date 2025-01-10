# Simulink PID Algorithm
This project is a Python-based lane detection system that uses OpenCV for real-time identification of road lanes. It combines Canny Edge Detection to identify edges and Hough Line Transform to detect lane lines in video frames. The model is optimized for accurate lane boundary detection, making it suitable for autonomous driving and road analysis tasks.

<img width="1281" alt="Screenshot 2024-10-08 at 8 53 05 PM" src="https://github.com/user-attachments/assets/19aa2886-ba62-40d1-84fc-d13ee020db7c">


## How It's Made:

**Tech used:** Python.

The lane detection system processes video frames that can be obtained typically from a dashcam by first converting each frame into a grayscale to simplify edge detection; then, A Gaussian blur is applied to reduce noise, which is then followed by canny edge detection to find the edges and potential lane boundaries. A region of interest is masked, and the Hough Line Transform detects straight lines within the region. Finally, detected lanes are overlapped onto the original video frame, providing real-time lane lines.

## Optimizations
Optimizing the lane detection system involves improving processing speed and accuracy. Using Gaussian blur helps reduce noise while keeping details needed for edge detection. I also had to determine the appropriate threshold for cany edge detection to ensure that only relevant edges were identified. 


