# 🎨 AI Vision-Based Color Detection  

## 🖥️ Detecting Colors Using OpenCV, NumPy, and Pillow  

### 📌 Overview  
This project utilizes **OpenCV, NumPy, and Pillow** to detect specific colors in real-time using a webcam. The program is currently set to detect **yellow**, but it can be adapted to detect other colors like red and black. The goal of this project was to **gain hands-on experience with AI vision techniques** and understand how **color detection** works in image processing.  

## 🚀 How It Works  
- The **webcam** captures frames in real-time.  
- The captured frame is **converted to HSV color space** for better color segmentation.  
- The color limits are **calculated dynamically** using a helper function.  
- A **binary mask** is applied to extract the specific color region.  
- If a **bounding box** is detected around the color, a **rectangle is drawn** around it.  
- The processed frame is displayed, and the detection continues until the user **presses 'q'** to exit.  

## 🛠️ Technologies Used  
- **Python** 🐍  
- **OpenCV** 👁️  
- **NumPy** 🔢  
- **Pillow (PIL)** 🖼️  

## 📂 Project Structure  
```
 ┣ 📜 main.py      # Runs the color detection logic using OpenCV
 ┣ 📜 util.py      # Defines helper functions for color limit calculation
 ┗ 📜 README.md    # Project documentation
```

## 📌 How to Run  
1. **Install dependencies:**  
   ```bash
   pip install opencv-python numpy pillow
2. **Run the program:**
   ```bash
   python main.py
3. **Press q to exit when done.**

## 🔥 Future Enhancements
- ✅ Add support for detecting multiple colors simultaneously.
- ✅ Improve bounding box accuracy with contour detection.
- ✅ Integrate deep learning models for object recognition.
- ✅ Implement real-time video recording of detected objects.

## 📜 License
This project is open-source and available under the MIT License.

## 📩 Contact
💡 Feel free to reach out via GitHub Issues if you have any questions or suggestions!
