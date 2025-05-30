## 🚗 Vehicle Detection & Counting using OpenCV and Deep Learning

This repository contains a complete implementation of a **Vehicle Detection and Counting** system built using **Python, OpenCV, and deep learning techniques**. The project detects vehicles in a video feed, tracks their movement, and counts them as they pass a designated virtual line. It’s ideal for smart traffic systems, automated surveillance, and intelligent transportation analytics.

---

### 🧠 Core Features

* 🎯 **Real-Time Vehicle Detection** using pre-trained object detection models (e.g., YOLOv3, MobileNet-SSD, etc.)
* 🔄 **Vehicle Tracking** with OpenCV tracking algorithms or centroid-based tracking
* ➕ **Counting Logic** to increment vehicle counts as they cross a user-defined line
* 📹 **Video Input Support**: Works with both recorded videos and live webcam feeds
* 📊 **Output Display**: Annotates detected vehicles with bounding boxes and real-time count overlay
* 🧰 Fully implemented in **Python (Jupyter Notebook)** for easy customization and testing

---

### 📁 Repository Contents

* `Vehicle_Detect_Count.ipynb`: Main notebook for vehicle detection and counting
* `/input`: Folder for storing your input video files
* `/output`: Folder for storing annotated output videos
* `utils.py` *(optional)*: Utility functions (e.g., drawing boxes, IO helpers)
* `requirements.txt`: Python dependencies

---

### 🛠️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/MahirHossain12/vehicle-detection-count.git
   cd vehicle-detection-count
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Vehicle_Detect_Count.ipynb
   ```

4. Upload or specify your video in the notebook and run all cells.

---

### 🧪 Optional Enhancements

* Integrate deep learning-based detectors (YOLOv5, SSD, Faster R-CNN)
* Add speed estimation and vehicle classification
* Deploy in Flask or Streamlit for real-time dashboarding
* Combine with traffic signal automation logic

---

### 📜 License

This project is open-source under the MIT License.

