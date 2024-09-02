# Emotion Detection using Audio Data

This project implements an emotion detection system that identifies two distinct emotions—**happy** and **sad**—using audio data. The model achieves a 100% accuracy rate on the testing dataset, making it highly reliable for distinguishing between these emotions.

## Features
- 🎧 **Emotion Detection:** Classifies audio clips into two categories: happy and sad.
- 🎼 **Input Format:** Accepts `.wav` files as input.
- 🎛️ **Data Processing:** Converts audio data into spectrograms for better feature extraction.
- 🧠 **Model Architecture:** Utilizes a Convolutional Neural Network (CNN) to analyze the spectrograms and predict emotions.
- ✅ **High Accuracy:** Tested on a comprehensive dataset with perfect accuracy.

## How It Works
1. **Audio Input:** Users provide `.wav` files as input.
2. **Spectrogram Conversion:** The audio files are converted into spectrograms, which are visual representations of the audio frequencies over time.
3. **CNN Processing:** The spectrograms are fed into a CNN model, which processes the data and outputs the detected emotion (happy or sad).

## Getting Started

### Prerequisites
- Python 3
- TensorFlow/Keras
- Tensorflow-io
- ffmpeg (for audio processing)
- Matplotlib (for spectrogram visualization)

### Installation
1. Clone the repository:
    ```bash
   git clone https://github.com/Ujjwal2017099/Emotion_Detection_Using_Audio_Data.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Emotion_Detection_Using_Audio_Data
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Results
The model has been thoroughly tested and consistently achieves 100% accuracy in distinguishing between happy and sad emotions in the provided audio samples.
