# Fashion-MNIST CNN Classifier (TensorFlow/Keras)

A Convolutional Neural Network (CNN) project to classify images from the **Fashion-MNIST** dataset into **10 clothing categories** using **TensorFlow/Keras**.  
The notebook covers an end-to-end workflow: data preparation → model building → training → evaluation (accuracy, confusion matrix, classification report).

## Project Overview
- Dataset: Fashion-MNIST (28×28 grayscale images, 10 classes)
- Model: CNN built with TensorFlow/Keras
- Output: Predicted class label for each image

## Workflow
1. **Load dataset**
2. **Preprocess data**
   - Normalize pixel values (0–1)
   - Reshape data for CNN input `(28, 28, 1)`
3. **Build CNN model**
   - Convolution + Pooling layers
   - Dense layers for classification
4. **Compile**
   - Optimizer: **Adam**
   - Loss: **Sparse Categorical Crossentropy**
   - Metric: **Accuracy**
5. **Train**
   - `model.fit()` with validation split / validation set
6. **Evaluate**
   - Test accuracy
   - Confusion matrix
   - Classification report
   - Sample predictions visualization

## Results
- Test Accuracy: **~86%** *(may vary depending on architecture/epochs)*
- Evaluation Included:
  - Confusion Matrix
  - Classification Report (precision/recall/F1 per class)

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn (confusion matrix & classification report)

## How to Run
### Option A — Jupyter Notebook
1. Clone the repo:
   ```bash
   git clone <YOUR_REPO_URL>
   cd <YOUR_REPO_FOLDER>
