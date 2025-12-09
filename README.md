🫁 Lung Cancer Detection using Deep Learning

This project focuses on building and evaluating deep learning models for lung cancer classification using CT-scan images. Multiple architectures—Xception, MobileNetV2, and InceptionV3—were trained and fine-tuned using different optimizers including Adam and Adagrad.
The goal is to compare their performance, analyze accuracy trends, and build a robust model suitable for medical-image classification tasks.

📁 Project Structure

├── DataSet1_Adam.ipynb
├── Lungcancerproject_adagrad.ipynb
├── README.md

🚀 Features

End-to-end deep learning pipeline

Image preprocessing and augmentation

Transfer Learning (Xception, InceptionV3, MobileNetV2)

Comparison of optimizers: Adam vs Adagrad

Fine-tuning for improved accuracy

Training history visualization

Evaluation on validation & test sets

🧠 Models Used

✔ CNN (Custom)

Basic model for baseline performance.

✔ Transfer Learning Architectures

Xception

MobileNetV2

InceptionV3

Each model was trained with:

Frozen base layers

Unfrozen fine-tuning stages

Batch size = 10

Input shapes:

Xception → 299×299×3

MobileNetV2 → 224×224×3

InceptionV3 → 299×299×3

🛠️ Tech Stack

Python

TensorFlow / Keras

NumPy

OpenCV

Matplotlib & Seaborn

| Model       | Optimizer | Best Accuracy | Notes                  |
| ----------- | --------- | ------------- | ---------------------- |
| Xception    | Adam      | High          | Best after fine-tuning |
| MobileNetV2 | Adam      | Moderate      | Lightweight model      |
| InceptionV3 | Adagrad   | Good          | Stable training        |

🧪 How to Run

Clone the repository

git clone https://github.com/your-username/lung-cancer-detection.git


Install dependencies

pip install -r requirements.txt


Open notebooks

jupyter notebook

📈 Training Visualization

Each notebook includes:

Accuracy & loss plots

Confusion matrix (optional)

Performance comparison

🩺 Real-World Relevance

Early detection of lung cancer significantly improves survival rates.
This project demonstrates how modern deep learning architectures can assist radiologists in identifying cancerous patterns from CT-scan imagery.

🤝 Contributions

Feel free to open an issue or submit a pull request to improve the model or add new datasets.
