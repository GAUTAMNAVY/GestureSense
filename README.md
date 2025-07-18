
<img width="2759" height="196" alt="image" src="https://github.com/user-attachments/assets/51388fc0-1e8b-4388-89b5-630b9d6ba4ee" />
## **Problem Statement**

In today’s digital environments—especially in education, remote work, and creative collaboration—traditional input devices limit natural interaction. Tasks like teaching online, drawing, or navigating software like OneNote can be inefficient without intuitive control. Existing systems lack support for contactless, gesture-based input that is both affordable and adaptable. There is a growing need for a real-time hand gesture recognition system that allows users to perform actions such as palm-to-select, point-to-hover, and pinch-to-draw. Such a system should be accurate, easy to use, and versatile enough to enhance accessibility, hygiene, and user experience across diverse applications like virtual classrooms, smart workplaces, and assistive tools.

## **Objectives**

- **Custom Dataset Creation**: Develop a self-recorded dataset of hand gestures to improve adaptability.  
- **Feature Extraction**: Implement image processing techniques to enhance gesture detection.  
- **Machine Learning Models**: Classify gestures using K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest (RF).  
- **Real-time Recognition**: Enable live gesture detection using a webcam.  
- **Future Integration**: Explore macro automation and implementation in 3D environments like Blender and other AR/VR Applications.  

## **Methodology**

### **1. Data Collection**
- Capture hand gesture images/videos using a webcam.  
- Preprocess images using image normalization, noise reduction, and edge detection techniques.  

### **2. Feature Extraction**
- Utilize contour detection, shape analysis, and pixel intensity patterns to extract meaningful features.  

### **3. Model Training and Classification**
- Implement and compare the performance of classification models:  
  - **KNN**: Classifies gestures based on nearest neighbor similarity.  
  - **SVM**: Enhances accuracy by defining optimal decision boundaries.  
  - **Random Forest**: Uses multiple decision trees to improve robustness and accuracy.  

### **4. Real-time Gesture Recognition**
- Process live webcam input to classify gestures in real time.  
- Integrate the system with automation tools like **Pyautogui** for macro execution.  

## **Technology Stack**

- **Programming Language**: Python  
- **Libraries & Frameworks**: Mediapipe, OpenCV, NumPy, Pandas, Scikit-learn, PyTorch, pyautogui  
- **Development Environment**: VS Code / PyCharm  

## **Expected Outcomes**

- A functional gesture recognition system capable of classifying custom hand gestures.  
- Improved model accuracy using machine learning techniques.  
- Real-time gesture recognition from a webcam.  
- Potential for further enhancements with neural networks and 3D applications.  

## **Future Scope**

- **Neural Networks**: Implement deep learning models for improved gesture recognition.  
- **3D Environment Integration**: Utilize gesture recognition for VR/AR applications and interactive 3D interfaces such as HCI and Assistive features for Disabled people (e.g., sign language translation to speech).  
- **Macro-based Automation**: Expand functionality for automating tasks using recognized gestures.  
