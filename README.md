# aerial-civilian-detection
Civilian detection system using drone vision and deep learning. Trained with Roboflow datasets and YOLO models, implemented in PyTorch. Detects civilians at various proximities in day/night conditions, with applications in surveillance, humanitarian aid, and defense research.

title: "🛰️ Aerial Civilian Detection"
repo_name: "aerial-civilian-detection"
short_description: "Civilian detection with drone vision and deep learning (YOLO, Roboflow, PyTorch)."
license: "Apache-2.0"
notice: |
  Copyright (c) 2025 YOUR_NAME
  This project is licensed under the Apache License 2.0. See LICENSE.
  A NOTICE file is included to preserve attribution and third-party notices.

badges:
  - alt: "Open In Colab"
    img: "https://colab.research.google.com/assets/colab-badge.svg"
    url: "PUT-YOUR-COLAB-LINK-HERE"
  - alt: "License: Apache-2.0"
    img: "https://img.shields.io/badge/License-Apache_2.0-blue.svg"
    url: "https://www.apache.org/licenses/LICENSE-2.0"

overview: |
  This project is a machine learning computer vision system that detects civilians in aerial or
  ground-level video streams. It is designed to identify civilians in both day and night settings,
  and at low and high proximities.

dataset:
  name: "Look Down Folks"
  source: "https://universe.roboflow.com/folks/look-down-folks"
  description: "Annotated imagery focusing on civilian/person detections suitable for aerial perspectives."

example_detections_markdown: |
  | Daylight Detection | Night Detection | High Proximity | Low Proximity |
  |--------------------|-----------------|----------------|---------------|
  | ![Day](images/day_detect.jpg) | ![Night](images/night_detect.jpg) | ![Close](images/close_detect.jpg) | ![Far](images/far_detect.jpg) |
  _Replace the `images/...` paths with your actual screenshots or GIFs._

how_to_use:
  option_1_colab: |
    **Run in Google Colab (Recommended)**
    Click the badge above to open and run this notebook directly in Google Colab (no installation required).
  option_2_local: |
    **Run Locally (VS Code or Jupyter)**
    1. Clone:
       ```bash
       git clone https://github.com/YOUR-USERNAME/aerial-civilian-detection.git
       cd aerial-civilian-detection
       ```
    2. Install dependencies:
       ```bash
       pip install -r requirements.txt
       ```
    3. Open `CivilianDetector.ipynb` in VS Code (with Jupyter extension) or Jupyter Notebook and run the cells.

tech_stack:
  - Python
  - YOLOv5/YOLOv8
  - Roboflow
  - OpenCV
  - PyTorch
  - Google Colab

results_section: |
  Add evaluation metrics here (if available):
  - Precision: XX.XX
  - Recall: XX.XX
  - mAP@0.5: XX.XX
  - mAP@0.5:0.95: XX.XX

limitations: |
  - May detect false positives when objects appear human-shaped.
  - Performance decreases in very low-light conditions unless enhanced with night vision.
  - Detection accuracy can vary with altitude, camera angle, and motion blur.

future_work: |
  - Improve robustness in low-light/infrared conditions.
  - Reduce false detections from non-human objects.
  - Optimize inference for real-time deployment on drones/edge devices.

ethical_note: |
  This project is strictly educational and created as part of an academic requirement.
  It is not intended for real-life military use without proper ethical evaluation and government oversight.

repo_structure_suggestion: |
  .
  ├── CivilianDetector.ipynb
  ├── requirements.txt
  ├── LICENSE
  ├── NOTICE
  ├── images/
  │   ├── day_detect.jpg
  │   ├── night_detect.jpg
  │   ├── close_detect.jpg
  │   └── far_detect.jpg
  └── README.md

topics:
  - computer-vision
  - object-detection
  - yolo
  - pytorch
  - opencv
  - drone-vision
  - aerial-imagery
  - civilian-detection
  - roboflow
  - colab

links:
  - label: "Dataset: Look Down Folks (Roboflow)"
    url: "https://universe.roboflow.com/folks/look-down-folks"
  - label: "Open In Colab"
    url: "PUT-YOUR-COLAB-LINK-HERE"

contributing: |
  Contributions are welcome via pull requests. By contributing, you agree that your contributions
  are licensed under the Apache License 2.0 and you grant the patent license specified therein.

citation_placeholder: |
  If you publish work using this repository, please cite it:
