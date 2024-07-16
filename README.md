# Volume-Hand-Control

## Overview
Volume Hand Control is a Python application that allows users to control the system volume using hand gestures. The application uses OpenCV for video capture and MediaPipe for hand tracking.

## Features
- Real-time hand detection and tracking
- Volume control through hand gestures
- Visual feedback with drawn connections and circles

## Requirements
- Python 3.7 or higher
- OpenCV
- NumPy
- MediaPipe
- Pycaw
- comtypes

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/VolumeHandControl.git
   cd VolumeHandControl

2. **Set Up a Virtual Environment**
   ```bash
   python -m venv .venv

3. **Activate the Virtual Environment On Windows:**

   ```bash
   .\.venv\Scripts\activate

4. **Install Required Packages:**
   
    ```bash
    pip install opencv-python numpy mediapipe pycaw comtypes

5. **Run the Application**
   
   ```bash
   python VolumeHandControl.py


### Control the Volume

- Bring your index finger and thumb close together to lower the volume.
- Move your fingers apart to increase the volume.

### Exit the Application

- Press `q` to quit the application.

### Code Explanation

- **HandTrackingModule.py:** Contains the implementation for hand detection using MediaPipe.

- **VolumeHandControl.py:** Main application that captures video, detects hand gestures, and controls the system volume.

### Troubleshooting

- If you encounter issues with missing imports, ensure all packages are installed correctly in your virtual environment.
- Make sure your camera is functioning properly and permissions are granted for video access.

### Acknowledgments

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [Pycaw](https://github.com/AndreMiras/pycaw)

### Collaborator
- [Hajeera Suhani](https://github.com/hajira25)

## License

- This project is licensed under the MIT License. See the LICENSE file for details.


