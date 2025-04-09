#  ASL Sign Language Detector using Deep Learning & Streamlit

This project is a beginner-friendly real-time **American Sign Language (ASL) Alphabet Detector** built using **Deep Learning**, **OpenCV**, and **Streamlit**. It allows users to either upload an image or use their **webcam** to detect and classify ASL signs.

##  Features

- ✅ Real-time ASL sign detection using your webcam
- ✅ Image upload-based sign recognition
- ✅ Deep learning model trained on the [ASL Alphabet Dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
- ✅ Streamlit web interface for easy interaction
- ✅ GitHub-ready and beginner-friendly

##  Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- Streamlit
- NumPy
- PIL (Pillow)

## Demo Screenshots

| Upload Image Mode | Webcam Mode |
|------------------|-------------|
| ![Upload Demo](https://github.com/user-attachments/assets/675f5bef-6c10-48f6-9a59-5f1c1a6e7cf3) | ![Webcam Demo](https://github.com/user-attachments/assets/569746dd-9800-4996-af9b-bf0fc373982e) |

##  Project Structure

asl-sign-language-app/ ├── app.py # Main Streamlit app ├── asl_model.keras # Trained deep learning model ├── labels.txt # Class labels (A-Z) ├── requirements.txt # Python dependencies ├── README.md # Project documentation └── screenshots/ # Demo images (optional)

##  How to Use

###  Run the App Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/AP154-png/asl-sign-language-detector.git
   cd asl-sign-language-detector
Install dependencies
pip install -r requirements.txt
Run the app
streamlit run app.py
View in your browser
Navigate to http://localhost:8501

Instructions
Upload Image: Upload a clear ASL alphabet image for prediction.
Use Webcam: Click “Start Webcam” to enable live detection.
Press Q to stop webcam mode.

 What is Deep Learning?
Deep Learning is a subset of Machine Learning that uses neural networks with many layers to learn complex patterns from data — similar to how the human brain works.

 Ideal For

Final year engineering/CS projects
Computer Vision learners
Beginners in Deep Learning & Streamlit
ASL/Accessibility awareness apps
🏁 Future Improvements

Add sentence-level gesture recognition
Build a mobile app version
Include voice feedback for each detected sign
� 
License
This project is open-source under the MIT License.

Author
Aparna Sajeevan
GitHub: AP154-png
