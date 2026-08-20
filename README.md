# YOLO Models Speed Comparison

A comparative experiment evaluating the inference speed of **YOLOv10n, YOLOv11n, and YOLOv12n** on a video using the Ultralytics YOLO framework.

## 📌 Project Overview

This project compares three lightweight YOLO models in terms of processing speed and FPS:

* YOLOv10n
* YOLOv11n
* YOLOv12n

The models were tested on the same video containing **942 frames**. The goal is to determine which model provides the best processing speed for video-based object detection and tracking.

## 🎯 Objectives

* Run multiple YOLO versions on the same video.
* Measure the total processing time for each model.
* Calculate the FPS achieved by each model.
* Compare the performance of YOLOv10n, YOLOv11n, and YOLOv12n.
* Identify the fastest model based on FPS and processing time.

## 🛠️ Technologies Used

* Python
* Google Colab
* Ultralytics
* YOLOv10
* YOLOv11
* YOLOv12
* OpenCV
* Pandas
* Matplotlib

## 📂 Project Structure

```text
YOLO-Speed-Comparison/
│
├── YOLO_SPEED.ipynb
├── YOLO_Results/
│   └── YOLO_speed_comparison.csv
│
└── README.md
```

## ⚙️ Installation

Install the required Ultralytics package:

```bash
pip install ultralytics
```

The project is designed to run in **Google Colab**.

## ▶️ How to Run

1. Open `YOLO_SPEED.ipynb` in Google Colab.
2. Run the installation cell.
3. Upload your video.
4. Run the notebook cells.
5. The three YOLO models will process the same video.
6. The notebook calculates processing time and FPS.
7. A comparison CSV file is generated.

## 📊 Experimental Results

The video contained **942 frames**.

| Model        |  Frames | Processing Time (s) |      FPS |
| ------------ | ------: | ------------------: | -------: |
| YOLOv10n     |     942 |              184.03 |     5.12 |
| **YOLOv11n** | **942** |          **183.97** | **5.12** |
| YOLOv12n     |     942 |              194.03 |     4.85 |

The results are generated and saved as a CSV file:

```text
/content/YOLO_Results/YOLO_speed_comparison.csv
```

## 🏆 Conclusion

Based on the experiment:

**YOLOv11n achieved the best speed performance**, with approximately **5.12 FPS** and the lowest processing time of **183.97 seconds**.

YOLOv10n achieved almost identical performance, while YOLOv12n had the lowest FPS and the highest processing time among the three tested models.

> **Note:** These results represent this specific experimental setup and should not be interpreted as universal benchmarks for the three YOLO versions.

## 📈 Visualization

The notebook also generates visual comparisons of the models' speed performance using Matplotlib.

## 📁 Output

The experiment produces:

* Processed tracking results for each YOLO model.
* Speed comparison visualization.
* `YOLO_speed_comparison.csv` containing the performance results.

## 👩‍💻 Author

**Sara Hassan**

AI & Data Science Student
Badr University in Assiut

---

⭐ If you find this project useful, feel free to give it a star!
