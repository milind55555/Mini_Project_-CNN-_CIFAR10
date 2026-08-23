# 🖼️ CIFAR-10 Image Classification Using CNN

A deep learning mini-project that uses a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** into 10 different categories.

## 📌 Project Overview

Image classification is one of the fundamental applications of computer vision and deep learning. In this project, a CNN model is developed using **PyTorch** to automatically recognize and classify small RGB images into their respective categories.

The model is trained on the **CIFAR-10 dataset**, which contains 60,000 color images of size 32×32 belonging to 10 classes.

The project covers the complete deep learning workflow:

**Dataset → Preprocessing → CNN Architecture → Training → Evaluation → Prediction**

## 🎯 Objectives

* Understand the fundamentals of Convolutional Neural Networks.
* Perform image preprocessing and normalization.
* Build a CNN model using PyTorch.
* Train the model on the CIFAR-10 dataset.
* Evaluate model performance on unseen test data.
* Visualize training performance.
* Understand the complete image-classification pipeline.

## 📊 Dataset

The **CIFAR-10 dataset** consists of:

* **60,000** color images
* Image size: **32 × 32 pixels**
* **10** classes
* 50,000 training images
* 10,000 test images

### Classes

1. ✈️ Airplane
2. 🚗 Automobile
3. 🐦 Bird
4. 🐱 Cat
5. 🦌 Deer
6. 🐶 Dog
7. 🐸 Frog
8. 🐴 Horse
9. 🚢 Ship
10. 🚚 Truck

## 🧠 CNN Architecture

The model consists of convolutional and pooling layers followed by fully connected layers.

Typical architecture:

```text
Input Image (3 × 32 × 32)
        ↓
Convolutional Layer
        ↓
ReLU Activation
        ↓
Max Pooling
        ↓
Convolutional Layer
        ↓
ReLU Activation
        ↓
Max Pooling
        ↓
Flatten
        ↓
Fully Connected Layer
        ↓
Output Layer
        ↓
10 Classes
```

## 🛠️ Technologies Used

| Technology       | Purpose                      |
| ---------------- | ---------------------------- |
| Python           | Programming language         |
| PyTorch          | Deep learning framework      |
| Torchvision      | Dataset and image utilities  |
| NumPy            | Numerical operations         |
| Matplotlib       | Data visualization           |
| Jupyter Notebook | Development environment      |
| CIFAR-10         | Image classification dataset |

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/cifar10-cnn-image-classification.git
cd cifar10-cnn-image-classification
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install torch torchvision numpy matplotlib jupyter
```

## 🚀 How to Run

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and execute the cells sequentially.

The notebook performs:

1. Dataset loading
2. Data preprocessing
3. Data visualization
4. CNN model creation
5. Loss and optimizer configuration
6. Model training
7. Model evaluation
8. Accuracy calculation
9. Prediction on test images

## 📈 Model Training

The CNN model is trained using:

* **Loss Function:** Cross Entropy Loss
* **Optimizer:** [Add your optimizer, e.g. Adam/SGD]
* **Epochs:** [Add number of epochs]
* **Batch Size:** [Add batch size]
* **Learning Rate:** [Add learning rate]

## 📊 Results

The trained CNN model was evaluated using the CIFAR-10 test dataset.

| Metric            |        Result |
| ----------------- | ------------: |
| Training Accuracy | [Add result]% |
| Test Accuracy     | [Add result]% |
| Number of Epochs  |   [Add value] |

> Replace the values above with the actual results from your training.

## 🔍 Sample Predictions

The trained model can be used to predict the class of previously unseen CIFAR-10 images.

Example:

```text
Actual Class: Dog
Predicted Class: Dog
```

You can add screenshots of your predictions, training graphs, or confusion matrix here.

## 📁 Project Structure

```text
cifar10-cnn-image-classification/
│
├── CIFAR10_CNN.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── sample_predictions.png
│   └── training_results.png
│
└── models/
    └── cifar10_cnn.pth
```

> Modify the file names according to your actual repository structure.

## 💡 Key Learnings

Through this project, I gained practical experience with:

* Convolutional Neural Networks
* Image preprocessing
* Tensor operations in PyTorch
* Convolution and pooling operations
* Activation functions
* Loss functions
* Backpropagation
* Gradient-based optimization
* Model evaluation
* Image classification

## 🔮 Future Improvements

Possible improvements include:

* Implementing data augmentation
* Adding Batch Normalization
* Using Dropout to reduce overfitting
* Experimenting with different CNN architectures
* Using learning-rate scheduling
* Generating a confusion matrix
* Improving test accuracy
* Comparing CNN performance with transfer-learning models such as ResNet or MobileNet

## 👨‍💻 Author

**Milind Hanchate**

B.Tech – Computer Science Engineering
Walchand Institute of Technology, Solapur

### 🔗 Connect With Me

* GitHub: [Your GitHub Profile](https://github.com/YOUR_USERNAME)
* LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/YOUR_USERNAME)

---

⭐ If you found this project useful, consider giving the repository a star!
