# Tensorflow Image Classifier
## A Brief Introduction
This project showcases a Python-based web application that leverages TensorFlow to classify images. Built with Streamlit, it provides a user-friendly interface where you can upload an image, and the application will use a pre-trained machine learning model to identify its contents. This project demonstrates the power of deep learning for image recognition in a simple, accessible way.

## Features
* Image Upload: Easily upload images in JPG or PNG formats.

* AI-Powered Classification: Utilizes the MobileNetV2 model, pre-trained on the ImageNet dataset, to classify uploaded images.

* Top Predictions: Displays the top 3 most likely predictions for the uploaded image, along with their confidence scores.

* User-Friendly Interface: An intuitive and interactive web interface powered by Streamlit.

## Tech Stack
This project is primarily built with Python and integrates powerful machine learning and web development frameworks:

* Python: The core programming language. This project specifically requires Python 3.11 or higher.

* Streamlit: Used for building the interactive web interface.

* TensorFlow: The foundational machine learning library, providing the MobileNetV2 model for image classification.

* OpenCV (cv2): Used for image preprocessing, including resizing and manipulating images to prepare them for the model.

* NumPy: Essential for numerical operations and array manipulation, especially when handling image data.

* Pillow (PIL): A widely used library for opening, manipulating, and saving many different image file formats.

## APIs Used
TensorFlow Keras Applications (MobileNetV2): This project utilizes the MobileNetV2 model, which is a pre-trained Convolutional Neural Network (CNN) available through TensorFlow's Keras Applications. It comes with weights pre-trained on the ImageNet dataset, allowing for powerful image classification without needing to train a model from scratch.

## Installation & Setup
To get a local copy of this project up and running, follow these simple steps:

### Prerequisites
Ensure you have Python 3.11 or higher installed on your system.

### Installation
* Clone the Repository:

git clone <your-repository-url>
cd Image-Classifier # Or the directory where your project files are located

* Set up Virtual Environment and Install Dependencies:
This project uses uv for dependency management. If you don't have uv installed, you can install it via pip:

pip install uv

* Then, create a virtual environment and install the project dependencies:

uv venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
uv pip sync

(Note: pyproject.toml lists the direct dependencies, and uv.lock contains the locked versions of all dependencies. uv pip sync ensures all locked dependencies are installed for a consistent environment.)

## Usage
Once installed and configured, you can run the AI Image Classifier from your terminal:

* Run the Streamlit Application:
Ensure your virtual environment is active, then execute the main.py script using Streamlit:

streamlit run main.py

This command will automatically open the application in your default web browser, typically at http://localhost:8501.

* Upload Your Image:
On the web interface, use the "Choose an image..." button to select and upload your image file (JPG or PNG).

* Classify Image:
Click the "Classify Image" button. The application will process your image, run it through the TensorFlow model, and then display the top classification predictions directly on the page.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

License
This project is open-source.

Contact
Zaahir Sharma - sharma.zaahir@gmail.com - https://www.linkedin.com/in/zaahir-sharma/

Project Link: [[https://github.com/zaahirsharma/Tensorflow-Image-Classifier](https://github.com/zaahirsharma/Tensorflow-Image-Classifier)]
