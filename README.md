# Brain Tumour Detection using Deep Learning

This project is a web-based application that detects brain tumors from MRI images using a deep learning (CNN) model.

## Features
- Upload MRI image and get prediction (Tumor / No Tumor)
- CNN model built with TensorFlow/Keras
- Flask web interface
- PDF report generation
- Simple and user-friendly UI

## Tech Stack
- Python
- TensorFlow / Keras
- Flask
- OpenCV
- NumPy, Pandas
- HTML, CSS, Bootstrap

## Project Structure
- app.py - main Flask app
- templates/ - HTML files
- static/ - CSS and JS files
- uploads/ - uploaded MRI images
- requirements.txt - project dependencies

## How to Run Locally
1. Clone the repository  
   git clone https://github.com/abhayyadav7/Brain-Tumour-Detection-using-Deep-Learning.git

2. Install dependencies  
   pip install -r requirements.txt

3. Run the project  
   python app.py

4. Open in browser  
   http://127.0.0.1:5000/

## Output
The system predicts whether the MRI image contains a brain tumor or not.
