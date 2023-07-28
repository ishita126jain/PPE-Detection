

# PPE Detection - Personal Protective Equipment Detection using YOLOv8 Object Detection




## 


![ss](https://github.com/ishita126jain/PPE-Detection/assets/91709949/0201e29c-e186-46d7-99fc-6104059af6fb)


## Introduction

PPE Detection is a Python-based project that employs YOLOv8, a robust object detection model, to identify and classify personal protective equipment (PPE) on construction sites. The project involves downloading a YOLOv8 model from Roboflow, training it on Google Colab, and using the best.pt model to detect PPE in images or videos.
## Prerequisites

- Python 3.6 or higher

- [Virtualenv](https://virtualenv.pypa.io/en/latest/) (optional but recommended)

## Installation

1. Create a virtual environment and activate it:

```bash
virtualenv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```
2. Install required packages:
```bash
pip install -r requirements.txt
```

## Training the Model
1. Download YOLOv8 model from Roboflow:

- Download the YOLOv8 model file from [Roboflow](https://universe.roboflow.com/) and place it in the weights/ directory.

2. Train the model on Google Colab:

- Follow the steps outlined in the colab file (Yolov8.ipynb) to train the model using your custom dataset.
## Usage

1. Prepare your video:

- Place your video file in the project directory.


2. Run the PPE Detection:
```bash
python PPE-Detection.py 
``` 

3. View the results:

- The processed video with PPE Detections will identifies and labels present equipment (e.g., "mask") and denotes absence as "no-mask" for each equipment type, providing accurate results.


## Configuration
- You can customize the confidence threshold for PPE detection by modifying the conf parameter in PPE-Detection.py. The default value is set to 0.5.
## Acknowledgements

 - [Ultralytics](https://github.com/ultralytics/ultralytics)
 - [CVzone library by CVzone](https://github.com/cvzone/cvzone)
 


## Contribution

Contributions are always welcome!

If you find any issues or have suggestions for improvements, feel free to create a pull request.


## Contact
For any questions or inquiries, please contact us at [ishita126jain@gmail.com](ishita126jain@gmail.com).
