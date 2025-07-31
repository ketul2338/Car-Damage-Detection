# 🚗 AI-Powered Car Damage Detection System

This project implements a deep learning-based system to detect visible car damages (scratches, dents, cracks) from images using **YOLOv8**. It can be used to automate car inspection in automotive, insurance, or rental sectors.

## 🔍 Features
- Detects damage regions in car images using YOLOv8 object detection.
- Highlights multiple types of damage (scratches, broken bumpers, etc.)
- Works on real-world datasets with noisy and varied backgrounds.
- Easy-to-use interface for uploading and testing new images (Streamlit version optional).

## 📁 Dataset
The dataset used for this project is publicly available on **Kaggle**:  
[Car Damage Detection Dataset on Kaggle](https://www.kaggle.com/datasets/)

> *Please download the dataset separately from Kaggle due to license restrictions.*

## 🛠️ Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-damage-detection.git
   cd car-damage-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in a folder named `dataset/`.

4. Run the notebook:
   ```bash
   jupyter notebook car-damage-detection-system.ipynb
   ```

## 🧪 Sample Results
<p align="center">
  <img src="assets/sample_output_1.jpg" width="400"/>
  <img src="assets/sample_output_2.jpg" width="400"/>
</p>

## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.  
Please give credit when using and do not use commercially or modify without permission.

Read the [LICENSE](LICENSE) file for more details.

## 🙏 Citation

If you use this work in your research or project, please cite:

```
@misc{patel2025cardamageai,
  author = {Patel, Ketul},
  title = {AI-Powered Car Damage Detection Using YOLOv8},
  year = {2025},
  howpublished = {\url{https://github.com/yourusername/car-damage-detection}},
}
```
