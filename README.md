# ASL Sign Language Recognition using Machine Learning

This project demonstrates the use of machine learning to recognize signs from the American Sign Language (ASL) alphabet. It utilizes a Random Forest classifier to classify images of ASL signs into their corresponding letters.  Hand tracking is performed using MediaPipe.

## Overview

American Sign Language (ASL) is a visual language used by the deaf and hard-of-hearing community. Automated recognition of ASL signs has numerous applications, including communication aids, educational tools, and accessibility solutions. This project aims to contribute to this field by providing a robust and accurate ASL sign recognition system.

## Features

* **Recognizes a subset of ASL signs:** The model is trained to recognize [Number] different ASL signs (specify the letters or a range, e.g., A-Z, or a specific set of signs).
* **Hand Tracking with MediaPipe:** Employs MediaPipe for accurate hand pose estimation and landmark detection. This allows for robust feature extraction even with variations in hand position and orientation.
* **Feature Extraction:**  Extracts relevant features from the hand landmarks detected by MediaPipe. These features are then used to train the machine learning model.
* **Random Forest Classifier:** Uses a Random Forest classifier for sign recognition. Random Forests are known for their robustness and ability to handle high-dimensional data.
* **Image-based Input:** The system processes static images of ASL signs as input.
* **[Optional: Real-time Recognition]:** [If you implemented real-time recognition using a webcam or video feed, mention it here].

## Technologies Used

* **Programming Language:** Python
* **Machine Learning Libraries:** scikit-learn
* **Computer Vision Library:** OpenCV
* **Hand Tracking Library:** MediaPipe
* **Data Processing Libraries:** NumPy
* **Data Persistence:** Pickle (for saving the trained model)
