# 🚗 YOLOv10, YOLOv11 & YOLOv12 Comparison for Real-Time Vehicle Detection and Tracking

This project benchmarks the performance of three YOLO models (YOLOv10n, YOLOv11n, YOLOv12n) for real-time object detection and tracking of vehicles in video streams. Each model is evaluated on accuracy, inference time, and FPS using a test video input.

## 📌 Project Goals

- Detect and track moving vehicles using different YOLO versions.
- Compare average inference time and FPS across YOLOv10, YOLOv11, and YOLOv12.
- Visualize model performance with frame snapshots and bar charts.

---

## 🛠️ Technologies Used

- Python
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- OpenCV
- PyTorch
- Matplotlib & Seaborn
- Pandas
- Jupyter Notebook

---

## 📦 Installation

Install all required packages:

```bash
pip install torch torchvision ultralytics opencv-python pandas matplotlib seaborn ipywidgets


📁 Folder Structure


YOLOvComparison/
│
├── yolov10n.pt
├── yolov11n.pt
├── yolov12n.pt
├── test1.mp4                # Sample input video
├── output_videos/           # Generated video outputs and plots
│   ├── YOLOv10n_tracked.mp4
│   ├── YOLOv11n_tracked.mp4
│   ├── YOLOv12n_tracked.mp4
│   ├── inference_speed_comparison.png
│   └── model_comparison_frames.png
├── notebook.ipynb           # Main Jupyter Notebook
└── README.md



▶️ How It Works
Load YOLO Models: Load pre-trained YOLOv10n, YOLOv11n, and YOLOv12n models using Ultralytics.

Run Object Detection & Tracking: Detect vehicles in every frame of the video and annotate with detection boxes and FPS.

Measure Performance: Compute average inference time and frames-per-second for each model.

Visualize Results:

Bar charts comparing average inference time and FPS.

Example frames from each model’s output.


📊 Sample Output
🔹 Inference Time vs FPS

🔹 Tracked Frames

```
