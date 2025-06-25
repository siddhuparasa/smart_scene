🎥 Smart Scene — AI-powered Video Summarization and Object Detection

**Smart Scene** is an AI-powered video analysis system that leverages **YOLOv7** to detect objects in each video frame, assign importance scores, and automatically summarize the video by selecting only the most meaningful high-quality frames.

It integrates:
- ✅ Real-time object detection
- ✅ Frame scoring based on object presence and relevance
- ✅ Automatic summarization of long videos
- ✅ Labeled objects with visual annotations

This project is ideal for **surveillance**, **sports analysis**, **content previews**, or any use case that needs concise, informative video summaries.

---

## 🚀 Key Features

- 🎯 **Object Detection**: Uses YOLOv7 (or YOLOv10 + ByteTrack) for high-speed object detection.
- 🧠 **Frame Scoring**: Assigns importance scores based on object frequency and detection confidence.
- ✂️ **Video Summarization**: Filters out unimportant frames and keeps key scenes.
- 🏷️ **Object Labeling**: Adds clear annotations to detected objects in output frames.
- 📈 **Evaluation Metrics**: Measures quality of summarization through frame and detection stats.

---

## 📽️ Demo Showcase

Take a look at how Smart Scene works in real-time. Below are both the raw input and the intelligently summarized output with object detection overlays.

### 🔹 🎬 Input Video — *Original Raw Footage*
▶️ [Click to Watch](https://drive.google.com/file/d/18WMLkKDjHzfOfOIN3Z5hGcsM-NcDjDHd/view?usp=sharing)  
> A standard video input with no filtering, used as the base for object detection and summarization.

---

### 🔹 ✅ Output Video — *AI-Generated Summary with Detected Objects*
🎯 [Click to Watch](https://drive.google.com/file/d/1z2B6LxjqZ_mK6vdjgLHf8zUyvGiYBU_j/view?usp=sharing)  
> This video highlights only the most important scenes, with real-time object annotations and scene compression powered by YOLOv7 + frame scoring.

---

🎉 **Smart Scene** filters out noise, reduces video length, and gives a quick, meaningful summary of what's truly important in the footage — with visual object tags!
---

## 🛠️ Tech Stack

- 🐍 Python
- 🧠 YOLOv7 / YOLOv10 (Object Detection Models)
- 🎥 OpenCV (Video Processing)
- 📊 NumPy, Matplotlib (Frame scoring, visualizations)
- ⚡ Google Colab (Notebook-based implementation)

---
