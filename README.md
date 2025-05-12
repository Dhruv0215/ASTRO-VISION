# ASTROVISION
A yolov8 based space staion object detection model trained using synthetic images.

# 🛰️ YOLOv8 Space Object Detection

This project detects space station objects like toolbox, fire extinguisher, and oxygen tank using a trained **YOLOv8 model**. The detection runs **live via webcam** or on **uploaded images**, and the UI is created with simple HTML, CSS, and JS.

---

## 📁 Project Structure

├── yolo/
│ ├── images/ # Raw dataset images (provided)
│ ├── data/ # Training data (labels + images)
│ ├── my_model/
│ │ └── best.pt # Trained YOLOv8 model
├── README.md



## ⚙️ How to Run the Project

### 🐍 Prerequisites

- Python 3.8 or above installed
- Anaconda installed
- YOLOv8 installed via `ultralytics`

---

### 🚀 Steps to Run (Windows with Anaconda)

#### Step 1: Open Anaconda PowerShell

- Search for **Anaconda PowerShell Prompt** in Start menu and open it

#### Step 2: Activate your YOLO environment (if you made one)

```bash
conda activate yolov8
(Or skip if you're using base environment)

Step 3: Navigate to your model directory
bash

cd path\to\yolo
Step 4: Run Live Detection with Webcam
bash

python "path to the python script provided" --model "path to your .pt file" --source 0(for webcam)

Step 5 : press q to exit
🧠 About the Model
YOLOv8 (Ultralytics)

Trained using custom annotated data (Label Studio)

Classes: Toolbox, Fire Extinguisher, Oxygen Tank


