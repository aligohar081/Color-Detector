

# **Real-Time Color Detection using OpenCV**

## **Overview**
This project detects and identifies colors in real-time using a webcam feed. The tool draws bounding boxes around detected colors and labels them with their names. Additionally, it provides features to:
- Identify HSV color values by clicking on the webcam feed.
- Save the current frame with detected colors.

---

## **Features**
1. **Real-Time Detection**: Detects multiple colors in real-time from a webcam feed.
2. **Color Labeling**: Draws bounding boxes around detected colors and labels them.
3. **HSV Color Picker**: Click on any point in the video feed to print the HSV value of the pixel.
4. **Frame Saving**: Save the current frame by pressing the `s` key.
5. **Extensive Color Range**: Includes a wide variety of colors and their shades.

---

## **Color Ranges**
The project detects the following colors:
- **Primary Colors**: Red, Orange, Yellow, Green, Blue, Purple.
- **Shades**: Light Green, Dark Green, Light Blue, Dark Blue, Lavender, Violet, Bright Red, Dark Red, and more.
- **Neutral Colors**: White, Gray, Black.
- **Additional Colors**: Pink, Cyan, Magenta, Teal.

---

## **Technologies Used**
- **Python**: Programming language.
- **OpenCV**: Library for computer vision tasks.
- **NumPy**: Library for numerical operations.

---

## **Setup Instructions**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-repo/color-detection.git
cd color-detection
```

### **2. Install Dependencies**
Make sure you have Python installed on your system. Install the required libraries:
```bash
pip install opencv-python
pip install numpy
```

### **3. Run the Project**
Execute the script:
```bash
python color_detection.py
```

---

## **Usage**

### **Key Features**:
1. **Detect Colors**:
   - Start the webcam feed.
   - The tool will automatically detect colors and draw bounding boxes with labels.

2. **Pick Colors**:
   - Click on any point in the video feed to print the HSV color value of that pixel in the console.

3. **Save Frame**:
   - Press the `s` key to save the current frame with bounding boxes.
   - The frame is saved as `saved_frame.jpg` in the current directory.

4. **Quit**:
   - Press the `q` key to quit the program.

---

## **Customization**

1. **Add More Colors**:
   - Add new colors to the `colors` dictionary in the `color_detection.py` file.
   - Example:
     ```python
     {"name": "Bright Pink", "lower": (160, 100, 100), "upper": (170, 255, 255)}
     ```

2. **Fine-Tune Color Ranges**:
   - Use the HSV color picker to get precise ranges for your desired colors.

3. **Adjust Thresholds**:
   - Modify the `cv2.contourArea(contour) > 500` condition to adjust the minimum object size for detection.

---

## **Examples**

### **Real-Time Detection**
![Real-Time Detection Example](https://via.placeholder.com/600x300.png?text=Real-Time+Detection+Example)

### **Saved Frame**
![Saved Frame Example](https://via.placeholder.com/600x300.png?text=Saved+Frame+Example)

---

## **Contributing**
Feel free to contribute by:
1. Adding new features.
2. Improving performance.
3. Extending the color detection capabilities.

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it.

---

## **Contact**
For questions or feedback:
- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub: [your-github-profile](https://github.com/your-github-profile)

---

Let me know if you'd like me to tailor this further or add details! 😊
