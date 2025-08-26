# face-detection-triangle
This project uses OpenCV and NumPy to detect faces in real time through a webcam and draws a triangle around each detected face instead of the usual rectangle.

🚀 Features:

Real-time face detection using your webcam
Triangular bounding instead of rectangular boxes
Press q to quit the window

🖥️ Demo:

When a face is detected, a green triangle will appear around it:

     /\
    /  \
   /____\

📦 Requirements:

Python 3.x
OpenCV
NumPy

Install dependencies using:
pip install opencv-python numpy

▶️ Usage:

Clone this repository:

git clone https://github.com/Himasri-codes/face-detection-triangle.git
cd face-detection-triangle


Run the script:

python face_triangle.py
A window will open showing the webcam feed with triangles drawn around detected faces.

🛠️ Code Overview:

Loads OpenCV’s pre-trained Haar Cascade for face detection.
Captures webcam video feed.
Converts frames to grayscale for faster processing.
Detects faces and draws triangles around them using NumPy + OpenCV.

📷 Controls:

q → Quit the application

📌 Example Use Cases:

Fun visualization for face detection projects
Creative demos for computer vision learning
Alternative to boring rectangles in CV applications

🤝 Contributing:

Feel free to fork this repo, open issues, and submit pull requests.
