# SRGAN Image Super Resolution Keras Project

This project uses a Super-Resolution Generative Adversarial Network (SRGAN) implemented in Keras to enhance image resolution. It involves several popular libraries for computer vision, deep learning, and scientific computing.

## 📆 Requirements

This project uses the following Python libraries:

- TensorFlow
- Keras
- OpenCV (cv2)
- NumPy
- Matplotlib
- scikit-image

These are listed in `requirements.txt`.

## 🔧 Setup

### 1. Clone the repository (or download the code)

```
git clone <your-repo-url>
cd SRGAN_keras
```

### 2. Create a virtual environment (optional but recommended)

```
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On macOS/Linux
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

## ▶️ Running the Script

Make sure your script (e.g., `SRCNN_main.py`) includes the right imports:
Then run the script:

```
python SRCNN_main.py
```

> Ensure any required datasets or input images are in the correct folder paths as referenced in your code.

## ❗ Notes

- Ensure you have Python 3.10 installed.
- TensorFlow 2.x is required for Keras to function properly.
- If `pip` isn't recognized, try using `python -m pip` instead.
