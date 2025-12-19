# Image Editing App

A Python-based Image Editing Application using Tkinter and OpenCV. This application allows users to view images, analyze their properties (histograms, statistics), and perform basic enhancements like equalization and brightness adjustment.

## Features

- **Image Viewing**:
  - Open images in various formats (JPG, PNG, TIF).
  - View individual bands of the image.
  - Resizeable image preview.

- **Image Analysis**:
  - **Statistics**: Calculate Minimum, Maximum, Mean, Standard Deviation, and Total pixel values for the image or specific bands.
  - **Histograms**:
    - View Standard Histograms.
    - View Cumulative Histograms.
    - View RGB Histograms (all bands).

- **Image Enhancement**:
  - **Histogram Equalization**: Perform histogram equalization on the image or specific bands to improve contrast.
  - **Brightness Control**: Adjust the brightness of the image (or specific bands).

## Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/Image_Editting_App.git
    cd Image_Editting_App
    ```

2.  **Install Dependencies**:
    The application requires Python 3.x and the following libraries:
    ```bash
    pip install opencv-python matplotlib pillow scipy scikit-image numpy
    ```

## Usage

1.  **Run the Application**:
    Execute the main script:
    ```bash
    python App.py
    ```

2.  **Using the App**:
    - Click **"Select file"** (or the Open button equivalent if labeled differently in UI updates) to load an image.
    - Use the dashboard to view dimensions and select bands.
    - Click **"Staticks"** to view image statistics.
    - Use the Histogram buttons to generate plots.
    - Use Equalization options to enhance the image.