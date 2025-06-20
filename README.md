# Emotional-Detection
This project uses DeepFace, a powerful deep learning facial analysis framework, along with OpenCV to detect and classify human emotions from facial images. The script analyzes static images to identify the dominant emotion expressed on a person's face and overlays that emotion label directly on the image.

## 🔍 Features
- Detects facial emotions such as:
  - 😊 Happy
  - 😢 Sad
  - 😠 Angry
  - 😮 Surprise
  - 😱 Fear
  - 🤢 Disgust
  - 😐 Neutral
- Automatically draws bounding boxes around faces.
- Overlays emotion labels on each detected face.
- Supports batch processing of multiple images.
- Fully compatible with **Google Colab** using `cv2_imshow()` for image display.

## 🛠️ Technologies Used
- Python
- OpenCV (`cv2`)
- DeepFace
- Google Colab (recommended environment)

## 📷 How It Works
1. Load facial images from local storage (e.g., `happy.jpg`, `anger.jpg`).
2. Analyze each image using `DeepFace.analyze()` with `emotion` action.
3. Detect face regions and dominant emotions.
4. Annotate the image with bounding boxes and emotion labels.
5. Display the final image in Colab.

## 🚀 Getting Started
To run this project in Google Colab:
1. Upload your facial images (`.jpg`, `.png`, etc.).
2. Install DeepFace:
   ```bash
   pip install deepface
Run the script to analyze and display emotions.

📁 Example Images
happy.jpg

sad1.jpg

anger.jpg

surprise.jpg

neutral.jpg

fear.jpg

disgust.jpg

📌 Use Cases
Emotion-aware AI applications

Facial sentiment analysis

Educational demos and research

Real-time user feedback systems

