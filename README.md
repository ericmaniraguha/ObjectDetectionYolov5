# YOLOv5 Configuration for Camera 0 Detection

Follow these steps to configure YOLOv5 to detect objects using Camera 0:

```bash
# 1. Clone YOLOv5 Repository:
git clone https://github.com/ultralytics/yolov5  # Clone repository
cd yolov5  # Navigate to repository directory

# 2. Create and Activate Environment:
conda create --name yolov5  # Create environment
conda activate yolov5  # Activate environment

```
# Ensure that you have at least Python version 3.7 installed.

```bash
# 3. Install Requirements:
pip install -r requirements.txt  # Install requirements

# 4. Run Detection Script with Local Video:
python detect.py --weights yolov5x.pt --source "E:\Computer Vision\video\01.mp4" --view -img

# Additional Options:
# - Adjust confidence threshold to 0.5 to filter detections:
python detect.py --weights yolov5x.pt --source "E:\Computer Vision\video\01.mp4" --conf-thres 0.5 --view-img

# - Adjust IoU (Intersection over Union) threshold to 0.5:
python detect.py --weights yolov5x.pt --source "E:\Computer Vision\video\01.mp4" --iou-thres 0.5 --view-img

# - Set both confidence and IoU thresholds to 0.5:
python detect.py --weights yolov5x.pt --source "E:\Computer Vision\video\01.mp4" --conf-thres 0.5 --iou-thres 0.5 --view-img

This is working on pre-trained weight.
```
