Face Recognition – Photo Classifier
This project helps organize a bunch of photos by detecting faces and grouping similar ones together.

🔍 What It Does
- Detects faces in images
- Groups photos of the same person into folders
- Makes it easier to manage large photo collections

🧰 Tools Used
- OpenCV – for reading and processing images
- face_recognition – to detect faces and get features
- DBSCAN – to group similar faces
- Python OS & Shutil – to manage files and folders

🖼️ Dataset
- Celebrity images with different expressions, angles, and lighting
- Includes challenges like glasses, hats, and different backgrounds

⚙️ How It Works
- Upload photos to a folder called input_photos
- The script detects faces and extracts features
- It groups similar faces using DBSCAN
- Saves grouped photos into folders like person_0, person_1, etc.

📁 Output
- A folder named classified_faces with subfolders for each person

✅ Conclusion
This project shows how face detection and clustering can help sort photos automatically. It’s useful for organizing albums or building smart photo apps.
