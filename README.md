# 🎭 Emotion Detection with DeepFace in Google Colab

This project demonstrates a simple yet effective implementation of emotion detection from facial expressions using the [DeepFace](https://github.com/serengil/deepface) library. It allows you to upload an image, detects faces, classifies the dominant emotion for each face, and displays the results with colored bounding boxes and context-aware feedback.

## 🧠 Key Features

- 🖼 Upload and analyze an image directly in Google Colab
- 😊 Detect emotions such as `happy`, `sad`, `angry`, `surprise`, `fear`, `disgust`, `neutral`, etc.
- 🧠 Generate custom AI responses based on detected emotions
- 🎨 Visual feedback using bounding boxes colored by emotion
- 📊 Displays results with `matplotlib` for easy viewing

## 🛠 Technologies Used

- Python
- Google Colab
- OpenCV (`cv2`)
- DeepFace
- NumPy
- Matplotlib

## 🚀 How to Run

### Step 1: Open Google Colab

Visit [https://colab.research.google.com](https://colab.research.google.com) and create a new notebook.

### Step 2: Paste the Code

Copy the entire code from the `main.ipynb` or the shared script.

### Step 3: Run the Notebook

1. The first cell installs dependencies (`deepface`).
2. The second part uploads your image.
3. Emotion detection and response generation will begin automatically.
4. Results will be displayed inline using `matplotlib`.

### Step 4: Upload an Image

When prompted by `files.upload()`, upload a **clear image containing at least one face**. The model will:

- Detect faces using DeepFace's detector.
- Predict the **dominant emotion** for each face.
- Display a response based on that emotion.

## 🖍 Example Output

- Bounding box in green for "happy"
- Emotion label displayed above the face
- Printed response like:
  > ✅ Detected Emotion: happy  
  > 💬 Response: I'm glad you're enjoying the lesson!

## 🧠 Emotion Mappings

| Emotion    | Box Color   | AI Response                                             |
|------------|-------------|----------------------------------------------------------|
| Happy      | Green       | "I'm glad you're enjoying the lesson!"                  |
| Sad        | Blue        | "Let's go over it again."                               |
| Angry      | Red         | "Frustrated? Let's break it down slowly."               |
| Surprise   | Cyan        | "Looks like something surprised you!"                   |
| Fear       | Purple      | "Don't worry, I'm here to help."                        |
| Disgust    | Teal        | "Something unclear? Let's clarify it."                  |
| Neutral    | Gray        | "Let's continue learning."                              |
| Confused   | Orange      | "You're confused. Let's go step by step."               |
| Dull       | Light Gray  | "You seem unengaged. Let's make this fun!"              |

## ⚠️ Notes

- Works best with **front-facing, well-lit images**.
- No need for webcam or real-time video in this version.
- Supports multiple faces in one image.

## 📌 Future Enhancements (Ideas)

- Real-time webcam capture using OpenCV
- Integration with adaptive learning platforms like VidyAI++
- Store logs of detected emotions for personalized feedback
- Use face landmarks for engagement analysis

## 📚 References

- [DeepFace GitHub](https://github.com/serengil/deepface)
- [OpenCV Documentation](https://docs.opencv.org/)
- [Emotion AI Research](https://en.wikipedia.org/wiki/Affective_computing)

---

© 2025 Namratha – Emotion-aware Learning Tools 💡
