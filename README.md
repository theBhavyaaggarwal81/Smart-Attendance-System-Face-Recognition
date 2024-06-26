# Smart Attendance System Face Recognition
A smart attendance system that automates attendance recording using advanced facial recognition technology.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to provide an efficient and accurate attendance recording system by leveraging facial recognition technology. It automates the process of attendance marking, reducing manual errors and saving time.

## Features
- Real-time face detection and recognition.
- Automated attendance recording.
- Easy to use and integrate with existing systems.
- Secure and reliable.

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

### Clone the Repository
```sh
git clone https://github.com/theBhavyaaggarwal81/smart-attendance-system-face-recognition.git
cd smart-attendance-system


Install Dependencies:
pip install -r requirements.txt


Run the Application:
python main.py


Usage:
1. Ensure your camera is connected and working.
2. Run the application using the command mentioned above.
3. The system will automatically detect and recognize faces, and record attendance.


Directory Structure:
smart-attendance-system/
├── data/
│   ├── known_faces/
│   └── unknown_faces/
├── models/
├── static/
├── templates/
├── app.py
├── encode_faces.py
├── recognize_faces.py
├── requirements.txt
└── README.md


Adding New Faces
1. Place the images of new individuals in the data/known_faces/ directory.
2. Run the encode_faces.py script to encode the new faces.
Command : python encode_faces.py


Contributing:
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.


License
This project is licensed under the MIT License - see the LICENSE file for details.

Developed by Bhavya Aggarwal (https://github.com/theBhavyaaggarwal81), Anubhav Bhatnagar, Sa,eeksha Ahuja, Devansh Rohilla.