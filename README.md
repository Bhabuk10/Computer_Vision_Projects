# Pothole Detection System using YOLOv8

This project aims to build a pothole detection system using YOLOv8 on a custom dataset. We have manually collected over 2000 pothole images, and the data annotation and augmentation are performed using Roboflow . The prepared dataset is then used to train a YOLOv8 model for detecting potholes.


## Installation and Dependencies

### Requirements

- Python 3.6 or higher
- Ultralytics YOLOv8
- Roboflow

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/pothole-detection-yolov8.git
    cd pothole-detection-yolov8
    ```

2. **Install Required Libraries**:
    ```bash
    pip install ultralytics==8.0.20
    pip install roboflow




### Code for Uploading Images to README

To include images in your README file, you need to upload the images to your repository and then use the appropriate Markdown syntax to display them. 

1. **Upload Images**:
    - Place your predicted images in the repository folder (e.g., `images/`).

2. **Include Images in README**:
    ```markdown
    ![Pothole 1](C:\Users\User\OneDrive\Desktop\Computer_Vision\Pothole_detection_using_YOLOv8\images\pothole_test.jpg)
    ![Pothole 2](C:\Users\User\OneDrive\Desktop\Computer_Vision\Pothole_detection_using_YOLOv8\images\val_batch0_pred.jpg)
    
    ```

Replace `images/predicted_pothole1.jpg`, `images/predicted_pothole2.jpg`, and `images/predicted_pothole3.jpg` with the actual paths to your images.
