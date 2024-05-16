# 🎨 AI Digit Recognition App
<!-- Intro  -->
<h3 align="center">
  <samp>&gt; Welcome to the AI Digit Recognition App!</samp>
</h3>

<p align="center"> 
  <samp>
    <br>
    「 A simple app to recognize hand-drawn digits using a CNN model 」
    <br>
    <br>
  </samp>
</p>

<p align="center">
 <a href="https://linkedin.com/in/ericivara" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
 </a>
 <a href="https://twitter.com/ericivara" target="_blank">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
 </a>
</p>

## ✨ Features

- **Digit Recognition:** The app can recognize hand-drawn digits (0-9) from user input.
- **Interactive Interface:** Users can draw digits on a canvas and get real-time predictions.
- **Top Predictions:** The app displays the top three predictions with their probabilities.

## 🖼️ Demo

Here's a short video of the app in action:
[video demo](https://private-user-images.githubusercontent.com/79364739/331321959-456dd37e-ffe3-4c16-b024-62390664ce6c.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU4ODE0OTksIm5iZiI6MTcxNTg4MTE5OSwicGF0aCI6Ii83OTM2NDczOS8zMzEzMjE5NTktNDU2ZGQzN2UtZmZlMy00YzE2LWIwMjQtNjIzOTA2NjRjZTZjLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA1MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNTE2VDE3Mzk1OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTkzZTE3ODI4MzJmZGU2OTMxZGJjNDVhY2I1ZjExMWZiNDllYzUzNzNhNjVlMjYyNThmODE1MmMzNmE5OWI4YTQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.rTmLwbFk_baQzxLEFdVWYz0FL8yMDWtc-jumwT18g8c)



## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF6F00?style=for-the-badge&logo=gradio&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)

## 🚀 Installation

To run this application locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/digit-recognition-app.git
    cd digit-recognition-app
    ```

2. **Install the required packages:**
    ```sh
    pip install numpy
    pip install tensorflow
    pip install gradio==3.39.0
    ```

## 🏃‍♂️ Running the Application

1. **Train the model:**
    ```sh
    python main.py
    ```

2. **Run the application:**
    ```sh
    python app.py
    ```

## 🎮 Usage

1. **Launch the app:** Once you run `python app.py`, the Gradio interface will be launched, and you can access it via a web browser.
2. **Draw a digit:** Use the canvas provided to draw a digit.
3. **Get Predictions:** The model will predict the digit and display the top three predictions with their probabilities.

## 📂 Code Overview

### `main.py`

- **Data Loading:** Loads the MNIST dataset.
- **Data Preprocessing:** Reshapes and normalizes the images.
- **Model Building:** Constructs a CNN with multiple layers.
- **Model Training:** Compiles and trains the model.
- **Model Saving:** Saves the trained model to `model.h5`.

### `app.py`

- **Model Loading:** Loads the pre-trained model.
- **Digit Recognition Function:** Defines a function to preprocess the input image and make predictions using the model.
- **Gradio Interface:** Sets up the Gradio interface to capture user input and display predictions.

## 🙏 Acknowledgments

- **TensorFlow/Keras:** For providing an excellent framework for building and training neural networks.
- **Gradio:** For making it easy to create interactive web interfaces for machine learning models.
- **MNIST Dataset:** For providing a standardized dataset for training and testing the digit recognition model.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
