**Fresh-or-Stale-Detector**



**Objective**: Fresh-or-Stale-Detector is a custom-trained YOLOv8 model that detects and classifies selected fruits and vegetables — apple, banana, orange, bitter gourd, capsicum, and tomato — as fresh or stale.


**Model Training**: Conducted in Google Colab using YOLOv8.

**Testing**: Performed locally in Python with .py scripts.

**Input**: Images of fruits and vegetables.

**Output**: Classification label (fresh / stale) and detection bounding boxes on the image.
Supported Files in Repository:

**best.pt** — Trained YOLOv8 model.

**Detection scripts**: e.g., detect_fresh_apple.py, detect_stale_tomato.py.

**Sample result images**: e.g., fresh_apple_result.png, stale_tomato_result.png.


**Usage**:
Install the required packages (YOLOv8, ultralytics, etc.).
Run detection scripts on your test images.
View results in the output images or console.
