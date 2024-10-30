
---

# 🌌 Crater Detection 🌌

A deep learning-powered web app that detects craters in images! Using a custom-trained YOLOv8 model on the OHRC dataset, this project aims to make crater detection accessible and simple through an interactive web interface.

---

## 🚀 Features

- **Custom YOLOv8 Model**: Specifically trained to detect craters using high-resolution OHRC satellite imagery.
- **Web-Based Interface**: Easily upload your own images to get instant crater detection results!
- **Quick and Intuitive**: Get real-time crater analysis with minimal setup.

---

## 🎬 Demo

**Try it yourself!**

1. Run the web app (instructions below).
2. Upload an image, and watch as craters are highlighted instantly!

![image0](https://github.com/user-attachments/assets/d64fae88-080e-47cb-af72-4bc104a477fe)

---

## 📥 Getting Started

### Prerequisites

- **Python**: Version 3.7 or higher.
- **Pip**: Ensure pip is installed to install the required packages.

### Installation

1. **Clone the Project**:
   ```bash
   git clone https://github.com/yourusername/Crater_Detection.git
   cd Crater_Detection
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Web App**:
   ```bash
   python webapp.py
   ```

4. **Access the App**:
   Open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000) to start detecting craters in your images!

---

## 🌍 Project Overview

Here's what you'll find in this repository:

- **`webapp.py`**: The main app file. This is where the magic happens! It launches a Flask server to handle user uploads and run crater detection on your images.
- **`yolo_model/`**: Directory where the YOLOv8 model files are stored.
- **`requirements.txt`**: List of dependencies needed to run the app.
- **`templates/`**: HTML templates for the web interface, giving it a clean and user-friendly layout.

---

## 📈 How it Works

Our **YOLOv8** model has been finely tuned on the **OHRC** (Optical High-Resolution Camera) dataset, a powerful set of high-quality satellite imagery specifically used for crater detection. By leveraging YOLO's real-time object detection capabilities, this model is able to spot craters with impressive accuracy.

### Model Training Details

The model was trained with custom parameters to maximize crater detection accuracy, optimized specifically for the OHRC dataset. Check out `training.md` (if available) for more information on the training process and dataset preparation.

---

## 🛠 How to Use Locally

Want to try it on your own machine? Here’s how!

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Crater_Detection.git
   cd Crater_Detection
   ```

2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App**:
   ```bash
   python webapp.py
   ```

4. **Open in Browser**:
   Once you see the link in your terminal (`http://127.0.0.1:5000`), open it in your browser to upload an image and detect craters on it!

---

## 💡 Tips & Tricks

- **Use Clear Images**: Crater detection works best with clear, high-resolution images.
- **Zoom In for Accuracy**: Larger craters are more likely to be detected accurately.
- **Experiment with Different Angles**: Satellite imagery from different angles can yield interesting results.

---

## 👥 Contributing

We welcome contributions! If you’d like to contribute, feel free to fork the repo, make your changes, and submit a pull request. Contributions to improve the model, web app UI, or add new features are all welcome.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🧑‍💻 Clone and Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Crater_Detection.git
   cd Crater_Detection
   ```

2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Web App**:
   ```bash
   python webapp.py
   ```

4. **Open in Browser**:
   Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) to upload and analyze your images!

---

Happy Crater Detecting! 🌌🌑
