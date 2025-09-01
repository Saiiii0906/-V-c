# निरVāc (Nirvāc) - AI Based Sign Language Translator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**निरVāc** is a real-time sign language translator designed to bridge communication gaps for the deaf and hard-of-hearing community. This project combines a powerful machine learning model with a minimal, privacy-first, and accessible user interface.

**Please note: This repository currently contains only the front-end portion of our project, showcasing the UI/UX design and the complete landing page.**

## 🚀 Real-Time Translation in Action

The core of our project is the machine learning model that interprets hand gestures from a live video feed. The model identifies hand landmarks, classifies the sign, and constructs sentences from the recognized gestures.


## ✨ Key Features

### 🖥️ Front-End & UI
* **Minimalist Design:** A clean, distraction-free interface that focuses on human connection.
* **Accessibility First:** Built to WCAG standards with high-contrast themes, full keyboard navigation, and respect for reduced motion preferences.
* **Privacy-Focused:** Prioritizes on-device processing to keep user data secure.
* **Fully Responsive:** A seamless experience across all devices.

### 🧠 Backend & Machine Learning Model
* **Real-Time Hand Tracking:** Uses advanced computer vision techniques to detect and track 21 key landmarks on each hand.
* **Gesture Classification:** A trained Multilayer Perceptron (MLP) model classifies the gestures for each letter of the alphabet (A-Z), space, and delete.
* **Sentence Construction:** Intelligently combines recognized signs to form coherent sentences.

## 🛠️ Tech Stack

* **Front-End:** HTML5, CSS3, JavaScript
* **Machine Learning:** Python
* **Core Libraries:** OpenCV, MediaPipe (for hand tracking), numpy ( for data manipulation), pytroch & touch.nn ( for building our core ASL model)

## ⚙️ How It Works

Our system processes sign language in a simple, three-step pipeline:

1.  **Capture:** The application captures video frames from the user's webcam at an efficient interval.
2.  **Interpret:** Our custom-trained model processes each frame to detect hand landmarks, maps the gestures to learned tokens, and predicts the corresponding letter or word.
3.  **Render:** The recognized text is presented on the user-friendly interface with low latency, allowing for a natural and uninterrupted conversation.

## 📦 Getting Started

### Running the Front-End Landing Page
1.  Clone this repository.
2.  Open the `index.html` file in your web browser.

### Running the Real-Time Translator
*(Instructions for setting up and running the Python backend would go here)*

1.  `pip install -r requirements.txt`
2.  `python app.py`
3.  Click the "Get Started" or "Try it out" button on the website to launch the `run.html` interface.

## 🤝 Our Team - "Tech Titans"

* **Raghav** - Backend Developer
* **Ankit** - Model Training & Testing
* **Nishant Chetry** - UI/UX & Interaction
* **SriSaiKiran T** - Front-end Developer
* **Anmol** - Dataset Model Developer

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
