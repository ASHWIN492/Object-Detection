# Object Detection using OpenCV

This Python script uses OpenCV to perform object detection in real-time using a pre-trained MobileNet SSD model.

## Requirements
- Python 3.x
- OpenCV
- coco.names file
- ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt file
- frozen_inference_graph.pb file

## Usage
1. Clone the repository or download the required files.
2. Make sure you have all the required files in the same directory as the script.
3. Run the script using Python:
4. The script will open a webcam feed and display real-time object detection results.

## Notes
- Make sure to adjust the threshold (`thres`) as needed for your specific use case.
- You may need to adjust the video capture settings (`cap.set()`) based on your webcam's specifications.
- The script will display detected objects with bounding boxes and confidence scores.

## Credits
- [OpenCV](https://opencv.org/) for the computer vision library.
- [COCO Dataset](https://cocodataset.org/) for the pre-trained model and class names.


