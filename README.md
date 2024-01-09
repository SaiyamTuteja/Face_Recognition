
# Face Recognition App

This Python script performs face recognition using the `face_recognition_module`. It captures video from the default camera, detects faces, and recognizes known faces, updating a real-time attendance log.

## Usage:

```bash
python Face_Recognition_app.py
```

### Dependencies:

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- face_recognition library

### Instructions:

1. Ensure you have the required dependencies installed (`cv2`, `NumPy`, `face_recognition`).
2. Place images of known faces (e.g., "saiyam.jpg", "yash.jpg") in the "faces" directory.
3. Run the script.
4. The camera will open, and recognized faces will be displayed with a "Present" label.
5. Press 'q' to exit the script.

### Known Issues:

- Make sure to position the faces appropriately in the "faces" images for accurate recognition.
- Adjustments may be needed based on your camera setup.

### Output:

- Real-time attendance log in a CSV file named with the current date (e.g., "dd-mm-yy.csv").

## License:

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
