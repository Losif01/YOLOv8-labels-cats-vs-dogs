# YOLOv8 Cat and Dog Detection with Visualization

This repository demonstrates using YOLOv8 to detect cats and dogs in images and visualize the results with bounding boxes.

## Functionality

1. **Object Detection:** The code leverages YOLOv8 (`yolov8m.pt`) to identify cats and dogs within an image.
2. **Prediction Results:** Detected objects (cats and dogs) are reported with their bounding box coordinates, confidence scores, and class labels.
3. **Visualization:** The script utilizes Pillow (PIL Fork) to create a visualization of the original image with bounding boxes drawn around the detected cats and dogs.

## Usage

This project is designed to be run as a Python script. Here's how to use it:

1. **Prerequisites:**
   - Python 3.x
   - Install YOLOv8 dependencies: `pip install ultralytics`

2. **Replace Image Path:**
   - Modify the script to point to the image you want to analyze. The current path is set to `/content/sample_data/cat_dog.png`. Replace this with the path to your image file.

3. **Run the Script:**
   - Execute the Python script (`catordog.ipynb` or equivalent) using a Python interpreter or a Jupyter Notebook environment.

## Output

The script will print the following information for each detected object:

- Object type (cat or dog)
- Bounding box coordinates (rounded)
- Confidence score (probability of detection)

Additionally, a visualization of the detected objects with bounding boxes will be displayed.

## References

- YOLOv8: https://github.com/ultralytics

## Disclaimer

While this script provides a basic example of cat and dog detection using YOLOv8, the accuracy may vary depending on the image quality and model configuration. For more robust results, consider training your own YOLOv8 model on a dataset specifically tailored to your needs.
