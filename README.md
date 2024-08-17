
# Sign Language Detection using OpenCV, MediaPipe, and Scikit-Learn

- This project implements a real-time sign language detection system using computer vision and machine learning techniques. 
- The system captures hand gestures via a webcam, detects and tracks hand landmarks using MediaPipe, and classifies the gestures into predefined sign language characters using a Random Forest classifier.





## Features

- Real-time hand landmark detection using MediaPipe.
- Capturing and preprocessing sign language gesture data.
- Training a Random Forest classifier to recognize gestures.
- Real-time gesture recognition and display.
## Prerequisites
- Python 3.9.0 or higher 
- Pickle
- OpenCV
- NumPy
- Matplotlib

## Installation

1. Clone the repository:

```bash
  git clone https://github.com/M-ED/Sign_Language_Detection_Python.git
```
2. Create virtual environment using following commands:
```bash
  conda create -n projects_CV python==3.9.0
  conda activate projects_CV
```

3. Install the necessary libraries in requirements file
```bash
   pip install -r requirements.txt
```

4. Prepare the Dataset
- Run the script to capture images for different classes (gestures).
- Store the images in the data directory under separate folders for each class.

5. Run the file using command
```bash
   python main.py
```
### Data Collection:
- Run the script to collect sign language gesture images.
- Modify `number_of_classes` and `dataset_size` as needed.

### Train the Model:
- Run the training script to train a Random Forest Classifier using the collected data.
- The trained model is saved as `model.p`.

### Real-time Gesture Detection:
- Run the detection script to start the webcam.
- The system will classify and display the detected gesture in real-time.


## Acknowledgements

- OpenCV: [https://opencv.org/](https://opencv.org/)
- TensorFlow [https://www.tensorflow.org/][https://www.tensorflow.org/]





## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Author

- [@mohtadia_naqvi](https://github.com/M-ED)

