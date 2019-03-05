"# recognize_faces" 

Face recognition program base on
https://github.com/ageitgey/face_recognition

Requirements:
Hardware
Nvidia GPU is recommend

Python library
numpy
dlib
face_recognition
pickle
imutils


Usage:
Step 1: Prepare dataset
python encode_faces.py --dataset dataset --encodings encodings.pickle
Step 2: Run the recognition code
Use the photo
python recognize_faces_image.py --encodings encodings.pickle --image photo.png
Use the video
python recognize_faces_video_file.py --encodings encodings.pickle --input video.mp4
Use the cam
python recognize_faces_video.py --encodings encodings.pickle
