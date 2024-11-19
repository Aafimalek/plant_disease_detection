# Plant Disease Recognition

This project is a web application designed to help farmers and agriculturalists recognize plant diseases using Machine Learning and Computer Vision. The application allows users to upload images of plants, detects diseases.

---

## Features
- **Disease Detection**: Uses a trained deep learning model to classify plant diseases from uploaded images.
- **Responsive Design**: User-friendly web interface built with HTML, CSS, and JavaScript.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning Libraries**: TensorFlow, NumPy, OpenCV, Pillow, Matplotlib
- **Deployment**: Docker, Google Cloud 

---

## Prerequisites

- **Python 3.7+**
- **Docker**
- **Google Cloud Platform** account

---

## Folder Structure

```plaintext
├── Dockerfile                   # Docker configuration for containerizing the app
├── app/                         # Main application code
│   ├── main.py                  # Flask app file
│   ├── models/                  # Pre-trained ML model(s)
│   ├── static/                  # Static assets (CSS, JavaScript, images)
│   └── templates/
│       └── index.html           # Frontend HTML file
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
