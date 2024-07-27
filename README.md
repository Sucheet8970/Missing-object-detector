# Missing Object Detector

## Overview
Welcome to the Missing Object Detector project! This tool uses YOLOv5, a cutting-edge object detection model, to identify and compare objects in images of the same scene taken at different times. The primary aim is to detect objects in both "before" and "after" images, identify any missing items, and provide a comprehensive list of detected objects. This is particularly useful for scenarios such as verifying the presence of items in spaces over time or identifying missing objects between two images.

## Features
- **Image Upload**: Allows users to upload two images of the same scene—one taken before and one after a certain event or period.
- **Object Detection**: Utilizes YOLOv5 for real-time object detection with high accuracy and speed.
- **Comparison**: Automatically detects and lists any missing objects by comparing the detected items between the two images.
- **Visualization**: Annotates and displays images with bounding boxes around detected objects for clear visual inspection.
- **Missing Items Identification**: Highlights items that are present in the "before" image but not in the "after" image.

## Requirements
- **Python 3.x**: Ensure you have Python 3.x installed on your system.
- **Google Colab**: Recommended for running the provided Jupyter notebook.
- **Libraries**:
  - `torch`: Required for running the YOLOv5 model.
  - `opencv-python`: Used for image processing tasks.
  - `google.colab`: Facilitates file uploads in Google Colab.

## Setup

### Clone the Repository
```bash
git clone https://github.com/Sucheet8970/Missing-object-detector.git
cd missing-object-detector
```

### Install Dependencies:
Install the necessary libraries using `pip`:
```bash
pip install torch torchvision opencv-python google-colab
```
### Run the Notebook:
Open and execute the Jupyter notebook in Google Colab to start the image upload and processing workflow.

## Usage
### Upload Images: Upload the "before" image first, followed by the "after" image when prompted.
Detection and Comparison: The notebook will process the images, detect objects, compare them, and identify any missing items.
### Results: View annotated images and lists of detected and missing objects.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributions
Contributions are welcome! Please fork the repository, create a new branch for your changes, and submit a pull request.
