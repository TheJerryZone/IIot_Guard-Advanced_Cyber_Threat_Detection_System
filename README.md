# IIOT Guard - Advanced Cyber Threat Detection for Industrial Networks

IIoT Guard is a secure, multi-user web application designed to detect cyber threats in Industrial Internet of Things (IIoT) networks using machine learning. It provides an easy-to-use web interface for uploading network traffic data, training multiple machine learning models, and classifying traffic into normal or malicious categories such as DDoS, Port Scanning, and Password attacks.

## Features

- User authentication with registration and login
- Upload network traffic data in CSV format
- Train and save machine learning models (Random Forest, SVM, Gradient Boosting, etc.)
- Multi-class classification of threats in IIoT network traffic
- View and download prediction results
- Responsive frontend built with HTML, Tailwind CSS, and JavaScript
- Secure password storage using hashing
- Session management and access control for core features

## Technology Stack

- Python 3.8+
- Flask web framework
- SQLite database for user management
- Scikit-learn for machine learning algorithms
- Pandas for data handling and preprocessing
- Tailwind CSS for UI styling
- JavaScript for client-side interactivity

## Installation

1. Clone the repository:

git clone <repository-url>
cd iiot-guard

2. Create and activate a Python virtual environment:

python -m venv venv
venv\Scripts\activate

3. Install required dependencies:

pip install -r requirements.txt

4. Set environment variables (example):

export FLASK_APP=app.py
export FLASK_ENV=development

5. Initialize the database:

flask initdb

6. Run the application:

flask run
Access the app at `http://localhost:5000`.

## Usage

- Register a new user account
- Log in with your credentials
- Upload a network traffic CSV file
- Select a machine learning algorithm to train a detection model
- View predictions on the uploaded data
- Download the detailed prediction results as a CSV file

## Project Structure

- `app.py` - Main Flask application and route definitions
- `models/` - Saved trained machine learning models and scalers
- `uploads/` - Uploaded CSV files storage
- `templates/` - HTML template files for frontend views
- `static/` - Static assets including CSS and JavaScript files

## Machine Learning Models Included

- Random Forest
- Decision Tree
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Extra Trees Classifier
- Logistic Regression
- Multi-Layer Perceptron (MLP)

## Limitations

- Batch processing only, no real-time traffic analysis
- Supports only CSV file format for uploads
- Models use default hyperparameters without automatic tuning
- Basic tabular results visualization without advanced dashboards

## Future Enhancements

- Real-time network traffic capture and analysis
- Support for additional data formats like PCAP
- Interactive visual dashboards for threat visualization
- Automated model selection and hyperparameter tuning
- Deployment using containerization and cloud services for scalability


## Acknowledgements

This project was completed as part of the Master of Computer Applications program at The National Institute of Engineering, Mysuru.

***

This README provides a comprehensive overview of the project, installation instructions, usage notes, and future directions aligning with your detailed project report. Let me know if you want it tailored specifically for certain GitHub features like badges or contribution guidelines.

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/44855525/6b7f09df-7b42-4c60-8615-c9696c869f99/final-report.pdf)
