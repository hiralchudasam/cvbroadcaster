# CV Broadcaster

CV Broadcaster is a Python-based web application for real-time video streaming and object segmentation using the YOLOv8 segmentation model. It enables users to process live video streams, apply advanced computer vision techniques, and visualize results directly in a web browser.

---

## Features

- 🔴 **Live Video Streaming:** Capture and broadcast video streams in real time.  
- 🟢 **Object Segmentation:** Leverage YOLOv8 for accurate and fast object segmentation.  
- 🟠 **Web Interface:** View and interact with processed video streams through a user-friendly web interface.  
- 🔵 **Modular Design:** Easily extend or modify components for custom computer vision tasks.

---

## Implementation

<!-- Add your screenshots below this line -->
![Screenshot 2025-05-09 124149](https://github.com/user-attachments/assets/5227fe99-3be7-4536-a63c-8cdc5b0021c3)

![Screenshot 2025-05-09 230816](https://github.com/user-attachments/assets/e9be287a-b7fb-4f29-9a7f-e41f5cfd3bbb)

![Screenshot 2025-05-09 230842](https://github.com/user-attachments/assets/bceecde5-18a4-48ae-b474-bb79303f0480)

![Screenshot 2025-05-09 230919](https://github.com/user-attachments/assets/e2d8528d-634c-4318-8705-a965e61e6dcb)

![Screenshot 2025-05-09 231022](https://github.com/user-attachments/assets/92b934c3-9476-421e-a2f3-cd885cc94b75)



---

## Getting Started

### Prerequisites

- Python 3.8 or higher  
- pip (Python package manager)

### Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/hiralchudasam/cvbroadcaster.git
    cd cvbroadcaster
    ```

2. **Install dependencies:**

    ```
    pip install -r requirements.txt
    ```

3. **Model Weights:**

    - Ensure `yolov8m-seg.pt` is present in the project root.  
    - If not, download the YOLOv8 segmentation weights from [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) and place them in the root directory.

---

## Usage

Start the application with:

- Open your web browser and go to `http://localhost:8000` (or the port specified in your configuration).  
- Start streaming and segmentation!

---

## Project Structure

main.py     – Application entry point

engine.py     – Core processing logic

stream_utils.py     – Video streaming utilities

yolov8m-seg.pt     – YOLOv8 segmentation model weights

requirements.txt     – Python dependencies

static/     – Static web assets (JS, CSS, images)

templates/     – HTML templates (if any)

.gitignore     – Git ignore file




---

## Customization

- **Change Model:** Replace `yolov8m-seg.pt` with your own YOLOv8 segmentation weights.  
- **Modify Processing:** Edit `engine.py` to implement new vision algorithms or change segmentation logic.

---

## Contributing

Contributions are welcome!  
Feel free to open issues or submit pull requests for features, bug fixes, or enhancements.

---


## Acknowledgments

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) for the segmentation model  
- OpenCV and other open-source libraries

---

*For questions or feedback, please open an issue on GitHub.*


