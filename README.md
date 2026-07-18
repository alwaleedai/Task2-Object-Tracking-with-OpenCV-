
# Task2 : 🎯 Object Tracking with OpenCV (Google Colab)
A simple, well-commented OpenCV project that tracks a moving object across video frames after you select it once with your mouse.

Track any object in a video using OpenCV directly inside **Google Colab** — no local setup or webcam required.

This notebook allows you to upload a video, select an object in the first frame, choose a tracking algorithm, and generate a tracked output video.

---
## 🎥 Demo

[▶️ View Demo](https://docs.google.com/videos/d/1s2s5H7YSE3WpDuauDybcRU6YJ8mq6JtiQiIpGnMFhbY/edit?usp=sharing)
---

## ✨ Features

- 📹 Upload any video
- 🎯 Manually select the object to track
- 🚀 Multiple tracking algorithms:
  - CSRT (Recommended)
  - KCF
  - MOSSE
- 💾 Automatically saves the tracked video
- ▶️ Preview the output directly inside Google Colab
- 📥 Download the final processed video

---

## 📂 Project Structure

```
object_tracking_colab.ipynb
README.md
```

---

## 🛠 Requirements

The notebook automatically installs the required packages:

```bash
opencv-contrib-python
ipywidgets
```

No manual installation is required when running in Google Colab.

---

## 🚀 How to Use

### 1. Open the notebook in Google Colab

Upload or open:

```
object_tracking_colab.ipynb
```

---

### 2. Install Dependencies

Run the first setup cell.

---

### 3. Upload Your Video

Choose any video file from your computer.

Supported formats include:

- MP4
- AVI
- MOV
- MKV

---

### 4. Choose a Tracker

Available options:

| Tracker | Speed | Accuracy |
|----------|-------|----------|
| CSRT | ⭐⭐ | ⭐⭐⭐⭐⭐ |
| KCF | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| MOSSE | ⭐⭐⭐⭐⭐ | ⭐⭐ |

**Recommended:** CSRT

---

### 5. Select the Object

Adjust the bounding box on the first frame until it surrounds the target object.

---

### 6. Run Tracking

The notebook will:

- Read every frame
- Track the object
- Draw the bounding box
- Save the output video

---

### 7. Preview & Download

The notebook automatically:

- Converts the video to a browser-friendly format
- Displays a preview
- Provides the final downloadable video

---

## 📷 Workflow

```
Upload Video
      │
      ▼
Choose Tracker
      │
      ▼
Select Object
      │
      ▼
Run Tracking
      │
      ▼
Preview Output
      │
      ▼
Download Video
```

---

## 📚 Tracking Algorithms

### CSRT
- Highest accuracy
- Best for most videos
- Slightly slower

### KCF
- Faster
- Good balance between speed and accuracy

### MOSSE
- Very fast
- Best for simple tracking scenarios

---

## 💡 Notes

- Designed specifically for **Google Colab**.
- No webcam is required.
- Works with uploaded video files.
- The first frame is used to initialize tracking.

---

## 🖥 Technologies Used

- Python
- OpenCV
- Google Colab
- ipywidgets

---

## 📄 License

This project is open source and available under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
