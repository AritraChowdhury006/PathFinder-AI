

🛣 Lane Lines Detection Using Python & OpenCV
This project implements a classic computer vision pipeline to detect lane lines in road images and driving videos. It uses color filtering, edge detection, region masking, and Hough Transform to identify lane markers and overlay them in real time.

📌 Features
Detects white and yellow lane lines using HSL color filtering
Applies Gaussian blur and Canny edge detection
Focuses on road area using dynamic region-of-interest masking
Uses Hough Transform to detect and draw lane segments
Processes both static images and video streams
Real-time visualization with OpenCV
⚙ Requirements
Python 3.6+
OpenCV (pip install opencv-python)
NumPy (pip install numpy)
🖼 For Image Detection
bash python lane_detection.py 

Make sure to update the image path in lane_detection.py to a valid file inside test_images.

🎥 For Video Detection
Replace the image section with video processing code (already included in the script). Use a valid .mp4 path from test_videos.

🧠 Future Enhancements
Curved lane detection using polynomial fitting
Temporal smoothing across frames
Deep learning-based segmentation (e.g., U-Net, SCNN)
📸 Demo
Add screenshots or a short GIF here to showcase results.
