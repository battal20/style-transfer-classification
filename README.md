### **Style Transfer and Image Classification with Deep Learning**

📌 **Project Overview**

This project explores the intersection of Neural Style Transfer and Image Classification using deep learning techniques. The goal is to transfer the artistic style of one image onto another while preserving content structure. After style transfer, deep feature extraction is applied to classify images based on their stylistic transformations. The methodology integrates VGG19 for style transfer, InceptionV3 for feature extraction, and contrastive learning for similarity measurement.

⚙️ **Methods Used**

Neural Style Transfer: Applied using a pre-trained VGG19 model to blend content and style features.

Feature Extraction: Used InceptionV3 to extract meaningful representations from transformed images.

Contrastive Learning: Implemented to compare content and stylized images based on feature similarity.

Data Augmentation: Random flips and rotations were applied to improve classification generalization.

Binary Classification: A classifier was trained to differentiate between original and stylized images.

🛠 **Technologies**

Python

Libraries: TensorFlow, NumPy, Matplotlib, PIL, Scikit-learn

🚀 **Getting Started**

Installation & Usage

1. Clone the repository:

   git clone https://github.com/YourUsername/Style-Transfer-Classification.git

2. Navigate to the project folder:

   cd Style-Transfer-Classification

3. Run the Jupyter Notebook:

   jupyter notebook blg454e-project-last.ipynb

🔮 **Future Enhancements**

Future improvements could include extending the project to multi-style transfer, where multiple artistic influences are blended into a single output. Additionally, integrating transformer-based vision models like ViT (Vision Transformer) could enhance feature extraction. Deploying an interactive web-based application for real-time style transfer and classification would make the project more accessible to users.
