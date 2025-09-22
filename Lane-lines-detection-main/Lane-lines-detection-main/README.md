
# 🛣️ Lane Lines Detection Using Python & OpenCV

This project implements a classic computer vision pipeline to detect lane lines in road images and driving videos. It uses color filtering, edge detection, region masking, and Hough Transform to identify lane markers and overlay them in real time.

## 📌 Features

- Detects white and yellow lane lines using HSL color filtering
- Applies Gaussian blur and Canny edge detection
- Focuses on road area using dynamic region-of-interest masking
- Uses Hough Transform to detect and draw lane segments
- Processes both static images and video streams
- Real-time visualization with OpenCV



## ⚙️ Requirements

- Python 3.6+
- OpenCV (\`pip install opencv-python\`)
- NumPy (\`pip install numpy\`)



### 🎥 For Video Detection

Replace the image section with video processing code (already included in the script). Use a valid \`.mp4\` path from \`test_videos\`.

---

Feel free to fork, modify, and build upon this project. Contributions are welcome!

