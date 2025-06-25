# 🎥 Smart Scene — AI-powered Video Summarization and Object Detection

Smart Scene is an **AI-powered video analysis system** that leverages **YOLOv7** to detect objects in each video frame, assign importance scores, and automatically summarize the video by selecting only the most meaningful high-quality frames.

It integrates:
- ✅ Real-time object detection
- ✅ Frame scoring based on object presence and relevance
- ✅ Automatic summarization of long videos
- ✅ Labeled objects with visual annotations

This project is ideal for surveillance, sports analysis, content previews, or any use case that needs concise, informative video summaries.

---

## 🚀 Key Features

- 🎯 **Object Detection**: Uses YOLOv7 (or YOLOv10 + ByteTrack) for high-speed detection
- 🧠 **Frame Scoring**: Assigns scores based on object frequency and confidence
- ✂️ **Video Summarization**: Keeps only important frames, filters noise
- 🏷️ **Labeling**: Annotates each detected object with names
- 📈 **Evaluation Metrics**: Includes summary quality measurements

---

## 📽️ Demo Videos

🔹 **Input Video**  
[▶️ Watch on Google Drive](https://drive.google.com/file/d/1z2B6LxjqZ_mK6vdjgLHf8zUyvGiYBU_j/view?usp=sharing)

🔹 **Summarized Output with Object Detection**  
[▶️ Watch on Google Drive](https://drive.google.com/file/d/18WMLkKDjHzfOfOIN3Z5hGcsM-NcDjDHd/view?usp=sharing)

---

## 🛠️ Tech Stack

- Python
- YOLOv7 / YOLOv10
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## 📂 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/siddhuparasa/SmartScene.git
   cd SmartScene
