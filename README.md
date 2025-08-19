# 🛰️ Aerial Civilian Detection

Civilian detection with drone vision and deep learning (YOLO, Roboflow, PyTorch).

This project is a **machine learning computer vision system** that detects civilians in aerial imagery.  
It is trained on drone-like datasets and can identify people at **day or night** and across **low and high proximity**.  

The model is trained in **Google Colab** and exported as a Jupyter Notebook (`.ipynb`) for easy use.  
👉 **You can download or open the notebook to run the full project yourself.**

---

## 🚀 Features
- Detects civilians from aerial or surveillance-like images.
- Works in both **day and night** scenarios.
- Handles **low and high proximity**.
- Trained on a custom dataset from [Roboflow Universe](https://universe.roboflow.com/folks/look-down-folks).
- Runs directly in **Google Colab** (no GPU setup needed).

---

## 📂 Project Files
| File | Description |
|------|-------------|
| `aerial_civilian_detection.ipynb` | Main Jupyter Notebook – full training, detection, and inference pipeline |
| `README.md` | Project overview and usage guide |
| `LICENSE` | Apache License 2.0 |

---

## 📊 Example Outputs
| Daytime Detection | Nighttime Detection |
|-------------------|---------------------|
| ![Day Example](https://via.placeholder.com/300x200.png?text=Daytime+Detection) | ![Night Example](https://via.placeholder.com/300x200.png?text=Nighttime+Detection) |

---

## ⚡ Quick Start
1. Clone this repo or download the `.ipynb` file.
2. Open the notebook in **Google Colab** or your local environment (VS Code / Jupyter).
3. Run all cells – model will train and then perform detections on test images or video streams.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](PUT-YOUR-COLAB-LINK-HERE)

---

## ⚠️ Limitations
- May produce **false positives** when objects resemble humans.  
- **Very low-light conditions** reduce detection accuracy (night vision support required for robustness).  
- Trained only on the civilian dataset → not optimized for soldier/combatant detection.  

---

## 📜 License
This project is licensed under the **Apache 2.0 License** – see the [LICENSE](LICENSE) file for details.  
✅ You are free to **use, modify, and share**, but must provide proper attribution.  

---

## 🙌 Acknowledgments
- Dataset from [Roboflow Universe – Look Down Folks](https://universe.roboflow.com/folks/look-down-folks).  
- Built with **YOLO**, **PyTorch**, and **Google Colab**.  
