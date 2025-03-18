Deep Fake Detection using Deep Learning

Project Overview

This project focuses on detecting deepfake videos and images using a deep learning model. Deepfakes, which manipulate facial appearances in videos using AI, pose a significant threat to digital security and authenticity. Our model leverages ResNeXt and LSTM architectures to effectively distinguish between real and fake media.

Team Members

This project was completed by the following students from MVJ College of Engineering:

Sujan J

Tejas S

Tharun Kumar G S

Uday Shankar B

Technologies Used

Python

TensorFlow/Keras

ResNeXt (Residual Network architecture)

LSTM (Long Short-Term Memory Network)

OpenCV

Django (for web deployment, if applicable)

Project Objectives

To develop an AI-based model that can accurately detect deepfake images and videos.

To leverage CNN-based architectures like ResNeXt for feature extraction.

To utilize LSTMs for sequential pattern recognition in videos.

To improve digital security by mitigating the risks posed by deepfake content.

Dataset

The model is trained on publicly available deepfake datasets, such as:

FaceForensics++

DFDC (Deepfake Detection Challenge dataset)

Celeb-DF

Implementation

Data Preprocessing: Frames are extracted from videos and processed for feature extraction.

Feature Extraction: ResNeXt is used to extract features from image frames.

Sequence Modeling: LSTM layers analyze temporal dependencies in videos.

Model Training: The model is trained using deepfake datasets.

Evaluation: Performance is measured using accuracy, precision, recall, and F1-score.

Results

The model achieved significant accuracy in detecting deepfake content, demonstrating the effectiveness of combining ResNeXt with LSTM networks.

Future Scope

Enhancing the dataset by including more real-world deepfake samples.

Improving model robustness against adversarial attacks.

Deploying the model as a real-time web application or browser extension.

How to Use

Clone the repository:

git clone https://github.com/your-repository/deepfake-detection.git
cd deepfake-detection

Install dependencies:

pip install -r requirements.txt

Run the model:

python detect.py --input path_to_video

View results and accuracy metrics.

Contributors

This project was developed as part of our academic work at MVJ College of Engineering.

License

This project is open-source under the MIT License. Feel free to contribute and improve upon our work!

For any queries or contributions, feel free to raise an issue or submit a pull request!

