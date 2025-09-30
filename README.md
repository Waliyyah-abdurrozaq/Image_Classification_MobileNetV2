# Image Classification with MobileNetV2

This project implements **image classification** using the **MobileNetV2** deep learning architecture.  
It is designed to classify images into different categories with efficiency and relatively low computational cost, making it suitable for mobile and embedded applications.

---

## Project Overview
- Pretrained **MobileNetV2** model (transfer learning)
- Fine-tuned for custom image dataset
- Supports training, evaluation, and prediction
- Notebook format: `Image_Classification_MobileNetV2.ipynb`

---

##  Repository Structure
Image_Classification_MobileNetV2/<br>
├── Image_Classification_MobileNetV2.ipynb # Jupyter notebook with full workflow <br>
├── requirements.txt # Python dependencies<br>
├── README.md # Project documentation<br>
└── data/ # Dataset used<br>


---

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Waliyyah-abdurrozaq/Image_Classification_MobileNetV2.git
   cd Image_Classification_MobileNetV2
2.  Create a virtual Environment

  python -m venv venv<br>
  venv\Scripts\activate

3. Install Dependencies<br>
pip install -r requirements.txt


---
## Usage
1. Open Jupyter Notebook
2. Run all cells in Image_Classification_MobileNetV2.ipynb.
3. Replace the dataset path with your own images for custom training.


---
## Results
- Achieved high accuracy on test data with transfer learning
- Model is suitable for deployment on lightweight devices
