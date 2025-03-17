# Image Comparison App – "Same or Not the Same?"

## Overview
Create a simple Streamlit app that allows users to upload two images and checks whether they are identical. 

## Technologies to Use
* **Python Libraries:** Streamlit, OpenCV (`cv2`), NumPy

## Installation
```bash
pip install streamlit numpy opencv-python
```

## Task Steps

### 1. Set Up the Streamlit App
* Create a Python script (`app.py`)
* Add an image upload section using `st.file_uploader()`
* If two images are uploaded, convert them to grayscale using OpenCV (`cv2`)
* Convert grayscale images into NumPy arrays
* Use `np.array_equal()` to check if the images are identical
* Display the result in Streamlit

### 2. Run & Test the App
* Start the app:
```bash
streamlit run app.py
```
* Open the provided URL in a browser and test image uploads

## Objectives
* Demonstrate image comparison using Python
* Create a user-friendly Streamlit interface
* Implement simple image processing techniques

## Bonus Challenges (Optional)
* Add error handling for invalid image uploads
* Implement a similarity threshold instead of exact match
* Display visual differences between images
