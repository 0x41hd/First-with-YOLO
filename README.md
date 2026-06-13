# Object and Video Detection using ImageAI and YOLOv3

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A localized computer vision project utilizing the **ImageAI** high-level wrapper framework to execute object detection on static images and dynamic video streams via the **YOLOv3** architecture.

## ⚙️ Features
* **Image Detection:** High-accuracy localization inside sample inputs (`max.jpg` and `cars.jpg`).
* **Probability Filtering:** Custom prediction rules ensuring bounding boxes only render above a 92% confidence metric threshold.
* **Video Analytics:** Frame-by-frame conversion processing running natively at 30 FPS.

## 🚀 Environment Setup (Windows 11 / Local)

### 1. Prerequisites
Make sure you have Python 3.11+ installed. Clone this repository and install the standard computer vision dependencies:

```bash
git clone [https://github.com/0x41hd/ImageAI_YOLOv3_Project.git](https://github.com/0x41hd/ImageAI_YOLOv3_Project.git)
cd ImageAI_YOLOv3_Project
pip install -r requirements.txt
