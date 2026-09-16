# TensorFlow: Data and Deployment

A collection of practical exercises for preparing TensorFlow data pipelines and deploying machine-learning models across web browsers, mobile and edge devices, reusable model services, and monitoring workflows.

## Portfolio Overview

| Area | Focus | Technologies and concepts |
| --- | --- | --- |
| TensorFlow.js | Browser-based machine learning | JavaScript, HTML, model conversion, transfer learning, webcam input |
| TensorFlow Lite | On-device inference | Model conversion, quantization, transfer learning, Android, iOS, Raspberry Pi |
| TensorFlow Datasets | Scalable data pipelines | `tf.data`, TFDS, TFRecord, feature columns, parallelization, custom datasets |
| Advanced deployment | Reusable models and monitoring | SavedModel, TensorFlow Hub, CNNs, TensorBoard, confusion matrices |

## Repository Sections

### 1. Browser-Based Models with TensorFlow.js

[`TensorFlow-JS/`](TensorFlow-JS/)

Exercises for training, converting, and running machine-learning models directly in a web browser.

Highlighted work:

- Iris and Wisconsin breast-cancer classifiers
- MNIST and Fashion-MNIST image classification
- Conversion of Keras models to TensorFlow.js format
- Cats-versus-dogs image classification
- Pretrained MobileNet and toxicity-detection models
- Rock-paper-scissors-lizard-Spock classification using webcam input
- Transfer learning and browser-based retraining

### 2. Device-Based Models with TensorFlow Lite

[`TensorFlow Lite/`](TensorFlow%20Lite/)

Projects focused on converting, optimizing, and executing TensorFlow models on mobile and edge devices.

Highlighted work:

- Converting TensorFlow models to TensorFlow Lite
- Fashion-MNIST on-device classification
- Transfer learning with TensorFlow Hub
- Rock-paper-scissors image classification
- Android and iOS image-classification examples
- Mobile object detection
- Raspberry Pi image classification and object detection
- Hyperparameter tuning and model optimization

### 3. Data Pipelines with TensorFlow Data Services

[`TensorFlow Datasets/`](TensorFlow%20Datasets/)

Notebooks demonstrating efficient ingestion, preprocessing, serialization, and delivery of data to TensorFlow models.

Highlighted work:

- Loading and exploring datasets with TensorFlow Datasets
- Rock-paper-scissors classification with TFDS
- Building input pipelines with `tf.data`
- Creating and reading TFRecord files
- Classifying structured data with feature columns
- Improving pipeline performance through parallelization
- Packaging a custom dataset for TensorFlow Datasets

### 4. Advanced Deployment Scenarios

[`Advanced Deployment Scenarios with TensorFlow/`](Advanced%20Deployment%20Scenarios%20with%20TensorFlow/)

Exercises covering reusable model formats, model sharing, serving concepts, and training visualization.

Highlighted work:

- Training an MNIST convolutional neural network
- Exporting models in SavedModel format
- Packaging and reusing a model through TensorFlow Hub
- Training a Fashion-MNIST classifier
- Monitoring model behavior with TensorBoard
- Visualizing how a confusion matrix changes during training

## Technologies

- **Machine learning:** TensorFlow, Keras, TensorFlow Hub
- **Deployment:** TensorFlow.js, TensorFlow Lite, SavedModel
- **Data engineering:** TensorFlow Datasets, `tf.data`, TFRecord
- **Languages:** Python, JavaScript, HTML, Swift, Java, Kotlin
- **Environments:** Jupyter Notebook, Google Colab, web browsers, Android, iOS, Raspberry Pi
- **Monitoring:** TensorBoard

## Project Structure

```text
TensorFlow_Data_and_Deployment/
├── TensorFlow-JS/
│   └── Browser-based training, conversion, and inference
│
├── TensorFlow Lite/
│   └── Mobile and edge-device model deployment
│
├── TensorFlow Datasets/
│   └── Data pipelines, TFRecord, TFDS, and custom datasets
│
├── Advanced Deployment Scenarios with TensorFlow/
│   └── SavedModel, TensorFlow Hub, and TensorBoard
│
└── README.md
```

Each main folder is organized by week and contains examples, exercises, model artifacts, datasets, or application code relevant to that deployment environment.

## Getting Started

### Clone the repository

```bash
git clone https://github.com/AI-YAZMIN-VILLEGAS/TensorFlow_Data_and_Deployment.git
cd TensorFlow_Data_and_Deployment
```

### Python notebooks

The notebooks can be opened in Jupyter or uploaded to Google Colab. For a local environment:

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter tensorflow tensorflow-datasets tensorflow-hub tensorflowjs numpy matplotlib
jupyter notebook
```

On Windows, activate the environment with:

```powershell
.venv\Scripts\activate
```

### TensorFlow.js examples

The browser examples should be served through a local web server rather than opened directly as local files. From the selected example directory, you can run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

### Mobile and edge examples

- Open Android projects with Android Studio.
- Open iOS projects with Xcode.
- Follow the included Python scripts and subfolder instructions for Raspberry Pi examples.

> These materials were developed with earlier TensorFlow ecosystem versions. Some notebooks or applications may require compatible legacy dependencies or minor API updates before running in a current environment.

## Skills Demonstrated

- Building reproducible TensorFlow input pipelines
- Serializing datasets and creating custom TFDS packages
- Training convolutional neural networks for image classification
- Converting models between Keras, TensorFlow.js, SavedModel, and TensorFlow Lite formats
- Applying transfer learning with pretrained models
- Running inference in browsers, mobile applications, and edge devices
- Integrating camera and webcam input with machine-learning models
- Optimizing models for constrained deployment environments
- Tracking training metrics and model behavior with TensorBoard
- Organizing deployment artifacts across multiple platforms

## About This Repository

This repository contains educational examples and completed exercises from the TensorFlow: Data and Deployment learning path. Course instructions, starter code, datasets, pretrained models, and referenced materials remain attributed to DeepLearning.AI, TensorFlow, Coursera, Laurence Moroney, and their respective authors.

## Author

**Yazmin Villegas**<br>
Data Analyst | Data Scientist<br>
[GitHub](https://github.com/AI-YAZMIN-VILLEGAS)

