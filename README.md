# 📏 Real-Time Object Measurement

This project implements **real-time object dimension measurements** using an image or a webcam. It leverages fundamental computer vision techniques along with the **OpenCV** library.

## 🛠️ Prerequisites

- Python 3.x
- OpenCV
- Numpy

## 📥 Installation

-> Install the required dependencies using pip: `pip install opencv-python numpy`.

## 🚀 Steps Involved

1. **Open the File**: Open the `main.py` file in a Python editor or IDE.
   
2. **Set Webcam or Image**: 
   - Set the `webcam` variable to `True` to use the webcam for detection.
   - Set it to `False` to process an image file.

3. **Provide Image Path**: If using an image file, provide the file path in the `path` variable.

4. **Adjust Video Capture Parameters**: Modify brightness, width, and height settings as needed using the OpenCV `cap.set()` function.

5. **Run the Script**: Execute the script by running `python main.py`.

6. **Observe Output**: 
   - If using the webcam, the script will start capturing video frames.
   - If using an image, it will process that image.

7. **Detect A4 Paper**: The script will detect A4-sized paper, overlaying a bounding box around it.

8. **Extract and Display**: Once detected, the script will warp the image to extract the paper and display it in a new window titled "A4." Detected objects within the paper will be highlighted with green polygons.

9. **Display Measurements**: For each detected object, the script will calculate and display its width and height in centimeters.

10. **View Original Image**: The original frame or image will appear in a window titled "Original."

11. **Exit Program**: Press **Ctrl + C** to exit the program.


### Working

If using the webcam, the script will start capturing video frames. If using an image, it will process that image. The script detects A4-sized paper in the frame or image, overlaying a bounding box around it. Once detected, it warps the image to extract the paper and displays it in a new window titled "A4." Any objects within the paper will be highlighted with green polygons. For each detected object, the script calculates and displays its width and height in centimeters. The original frame or image appears in a window titled "Original." Press **Ctrl + C** to exit the program.

## 📚 Resources

- [OpenCV Documentation](https://docs.opencv.org/)
- [Python Documentation](https://www.python.org/doc/)

---
