# 🎨 Color Detection using Python and OpenCV

A computer vision project that detects colors in images or video streams using Python and OpenCV. It identifies colors based on their RGB values and displays the corresponding color name and color values.

## 🚀 Features

* Real-time color detection using a webcam.
* Identifies colors based on pixel values.
* Displays the detected color name and RGB values.
* Uses mouse interaction to select pixels and identify their colors.
* Simple and interactive computer vision application.

## 🛠️ Tech Stack

* **Python** — Core programming language.
* **OpenCV** — Image processing and computer vision.
* **Pandas** — Color dataset handling and color name lookup.
* **NumPy** — Numerical operations on image data.

## 📂 Project Structure

```text
Color-Detection/
├── main.py
├── colors.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd Color-Detection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python main.py
```

## 🧠 How It Works

1. **Image Input:** The application loads an image or captures video from a webcam.
2. **Pixel Selection:** The user selects a pixel using the mouse.
3. **Color Extraction:** OpenCV extracts the pixel's color values.
4. **Color Identification:** The application compares the extracted values with a color dataset to identify the closest matching color.
5. **Display:** The detected color name and its corresponding color values are displayed on the image.

## 📚 Learning Outcomes

* Understanding fundamental computer vision concepts.
* Working with images and pixels using OpenCV.
* Handling mouse events in OpenCV windows.
* Understanding RGB and BGR color representations.
* Building an interactive Python application.

## 🔮 Future Improvements

* Extend color detection to live video streams.
* Improve color matching using color-distance calculations.
* Add HSV-based color detection.
* Develop a graphical user interface.
* Explore real-time object and color tracking.

## 👨‍💻 Author

**Ishan**

Computer Vision | Python | OpenCV

---

If you find this project useful, consider giving the repository a ⭐.
