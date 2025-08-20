### Face Detection & Recognition
This project is a real-time Face Detection and Recognition System developed using Python, OpenCV, and Deep Learning (Keras/TensorFlow).
It allows you to collect facial data, preprocess it, train a CNN model, and perform real-time face recognition using a webcam or IP camera feed.

Face detection and recognition are among the most important applications in computer vision.
This project demonstrates:

- **Face Detection** using Haar Cascade Classifier (OpenCV).  
- **Face Recognition** using a trained **Convolutional Neural Network (CNN)**.  
- Ability to capture and process **custom face datasets** for training.  
- Real-time recognition from live camera streams.

---

## 📂 Project Structure  

```
├── collect_data.py               # Captures face images from webcam/IP camera
├── consolidated_data.py          # Preprocesses collected data into pickle format
├── face_detection.py              # Trains a CNN (LeNet architecture) on dataset
├── recognize.py                   # Runs real-time face recognition
├── final_model.h5                 # Trained CNN model (output after training)
├── haarcascade_frontalface_default.xml  # Haar Cascade Classifier for face detection
├── images/                        # Folder of collected face images (optional)
└── README.md
```

---
##  Technologies Used  

- **Programming Language**: Python 3  
- **Libraries/Frameworks**:  
  - OpenCV (cv2) → Face detection & image processing  
  - TensorFlow / Keras → Deep Learning CNN model  
  - NumPy → Array manipulations  
  - Matplotlib → Visualization  
  - Scikit-learn → Label encoding  

---

## 🚀 How to Run  

### 1. Clone the Repository  
```bash
git clone https://github.com/<your-username>/Face-Detection-Recognition.git
cd Face-Detection-Recognition
```

### 2. Install Dependencies  
Create a virtual environment (recommended) and install requirements:  
```bash
pip install -r requirements.txt
```

### 3. Collect Data  
Capture 100 face samples per person:  
```bash
python collect_data.py
```

### 4. Preprocess Data  
Convert images into pickle files for training:  
```bash
python consolidated_data.py
```

### 5. Train the Model  
Train CNN (LeNet architecture) and save as `final_model.h5`:  
```bash
python face_detection.py
```

### 6. Run Real-Time Recognition  
Start live recognition using webcam/IP camera:  
```bash
python recognize.py
```

---

## Demo  

(Add screenshots or GIFs here of:  
- Data collection window  
- Model training accuracy graph  
- Real-time recognition with bounding boxes & labels)  

---
