# 🧍 Pose Detection using OpenCV & MediaPipe

A real-time human pose detection project built using **Python, OpenCV, and MediaPipe**.

This project uses a webcam to detect human body landmarks in real time and displays the detected pose on the live video feed.

## 🚀 Features

- Real-time webcam video capture
- Human pose detection
- Human body landmark detection
- Pose skeleton visualization
- Real-time FPS calculation
- Live video processing using OpenCV
- Real-time pose tracking
- Simple Python implementation

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming language |
| OpenCV | Image and video processing |
| MediaPipe | Human pose detection |

## 📥 Installation

### 1. Clone the Repository

    git clone https://github.com/Akhil-Sheelam/Pose_detection.git

### 2. Navigate to the Project

    cd Pose_detection

### 3. Install Required Libraries

    pip install opencv-python mediapipe

## ▶️ How to Run

Run the following command:

    python main.py

The application will:

1. Open the computer's webcam.
2. Capture the live video.
3. Detect the human body.
4. Identify body landmarks.
5. Draw the pose skeleton.
6. Display the real-time FPS.

Press **Q** to close the application.

## 🔍 How It Works

The project uses **OpenCV** for webcam access and video processing and **MediaPipe Pose** for detecting human body landmarks.

### Workflow

    Webcam
       ↓
    OpenCV Video Capture
       ↓
    Video Frame
       ↓
    MediaPipe Pose Detection
       ↓
    Body Landmarks
       ↓
    Pose Visualization
       ↓
    FPS Calculation
       ↓
    Live Display

### Step-by-Step Process

**1. Capture Video**

OpenCV accesses the computer's webcam and continuously captures video frames.

**2. Process the Frame**

Each frame is processed before being sent to the pose detection model.

**3. Detect Pose**

MediaPipe analyzes the frame and detects human body landmarks.

**4. Draw Landmarks**

The detected landmarks and connections between them are drawn on the video frame.

**5. Calculate FPS**

The application calculates the number of frames processed per second and displays the FPS.

**6. Display Result**

The processed frame is displayed in real time.

## 🧍 Pose Landmarks

MediaPipe Pose can detect multiple landmarks on the human body.

| Body Part | Example |
|-----------|---------|
| Face | Nose |
| Upper Body | Shoulders |
| Arms | Elbows |
| Hands | Wrists |
| Torso | Hips |
| Legs | Knees |
| Feet | Ankles |

Each detected landmark can provide information such as:

- Landmark ID
- X Coordinate
- Y Coordinate
- Z Coordinate
- Visibility

This information can be used for calculating body angles, movement, distance, and posture.

## 💡 Possible Applications

This project can be extended to build:

- Fitness tracking applications
- Exercise repetition counters
- Sports movement analysis
- Posture detection
- Workout monitoring
- Gesture recognition
- Human activity recognition
- Movement tracking systems

## 📂 Project Structure

    Pose_detection/
    │
    ├── main.py
    ├── pose_detection.py
    └── README.md

### main.py

The main application file responsible for:

- Webcam initialization
- Video capture
- Frame processing
- Pose detection
- FPS calculation
- Live video display

### pose_detection.py

Contains the pose detection functionality using MediaPipe.

It is responsible for:

- Processing frames
- Detecting pose landmarks
- Drawing landmarks
- Drawing pose connections
- Extracting landmark information

## 📋 Requirements

### Software

- Python 3.x
- Working webcam
- Windows / Linux / macOS

### Python Libraries

- OpenCV
- MediaPipe

Install the required libraries:

    pip install opencv-python mediapipe

## 🔮 Future Improvements

- [ ] Exercise repetition counter
- [ ] Push-up detection
- [ ] Squat detection
- [ ] Plank detection
- [ ] Posture correction
- [ ] Multiple-person pose detection
- [ ] Exercise classification
- [ ] Workout tracking
- [ ] Pose angle calculation
- [ ] Save pose data
- [ ] Generate workout reports
- [ ] Add graphical user interface
- [ ] Add real-time alerts
- [ ] Improve camera error handling

## 🐛 Troubleshooting

### Webcam is Not Opening

If the webcam does not open:

- Make sure the webcam is connected.
- Check camera permissions.
- Close other applications using the webcam.
- Restart the application.

### ModuleNotFoundError

If you see:

    ModuleNotFoundError: No module named 'cv2'

Install OpenCV:

    pip install opencv-python

If MediaPipe is missing:

    pip install mediapipe

### Camera Permission Error

Make sure Python or your terminal/application has permission to access the camera.

On Windows:

    Settings
       ↓
    Privacy & Security
       ↓
    Camera

Make sure camera access is enabled.

### Low FPS

If the application is running slowly:

- Close unnecessary applications.
- Reduce the webcam resolution.
- Make sure your system has sufficient CPU resources.
- Avoid running multiple camera applications simultaneously.

## 🎮 Controls

| Key | Action |
|-----|--------|
| Q | Exit the application |

## 📸 Demo

Run the application:

    python main.py

The webcam window will display:

- Live camera feed
- Detected body landmarks
- Pose connections
- Real-time FPS

## 📚 Learning Outcomes

This project demonstrates practical implementation of:

- Python
- OpenCV
- MediaPipe
- Computer Vision
- Real-Time Video Processing
- Human Pose Estimation
- Webcam Processing
- Landmark Detection

## 👨‍💻 Author

**Akhil Sheelam**

GitHub: https://github.com/Akhil-Sheelam

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

## 📄 License

This project is created for educational and learning purposes.
