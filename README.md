# Same or Not the Same? - Image Comparison Streamlit App

## Overview

This Streamlit application allows users to upload two images and determine whether they are identical. The app provides a simple, user-friendly interface for comparing images using Python and computer vision techniques.

## Project Description

The "Same or Not the Same?" app enables users to:
- Upload two images
- Convert images to grayscale
- Compare image matrices 
- Determine if the images are exactly the same

## Technologies Used

- **Python**
- **Streamlit**: Web application framework
- **OpenCV (cv2)**: Image processing
- **NumPy**: Numerical computing

## Prerequisites

- Python 3.7+
- pip package manager

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-comparison-app.git
   cd image-comparison-app
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install required dependencies:
   ```bash
   pip install streamlit numpy opencv-python
   ```

## Running the Application

1. Navigate to the project directory
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

3. Open the provided local URL in your web browser

## How to Use

1. Upload the first image
2. Upload the second image
3. The app will automatically compare the images
4. View the result: "Same" or "Different"

## Project Structure

```
image-comparison-app/
│
├── app.py           # Main Streamlit application
├── README.md        # Project documentation
└── requirements.txt # Dependency list
```


