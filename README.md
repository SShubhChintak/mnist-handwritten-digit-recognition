# Handwritten Digit Recognition Using Neural Networks (MNIST Dataset)

An educational image-classification project that recognizes handwritten digits from **0 to 9** using the MNIST dataset and a **Convolutional Neural Network (CNN)** built with Python and TensorFlow/Keras.

## Project overview

The MNIST dataset contains 70,000 grayscale images of handwritten digits. Each image is 28 × 28 pixels, with 60,000 training images and 10,000 test images. The project demonstrates image loading and exploration, preprocessing, neural-network development, training, testing, performance evaluation, and an interactive digit-recognition interface.

## Key features

- Loads and explores the MNIST handwritten-digit dataset.
- Normalizes image pixel values to the range [0, 1].
- Trains a CNN to classify ten digit classes.
- Evaluates the model using accuracy, loss, a classification report, and a confusion matrix.
- Visualizes sample predictions and misclassified test images.
- Provides a Gradio interface for drawing or uploading a digit.
- Offers white and black drawing-brush colours, prediction confidence, top-three predictions, and a processed 28 × 28 image preview.
- Saves and reloads the trained model in Keras format.

## Dataset

| Property | Description |
|---|---|
| Dataset | MNIST Handwritten Digits |
| Total images | 70,000 |
| Training images | 60,000 |
| Testing images | 10,000 |
| Image size | 28 × 28 pixels |
| Image type | Grayscale |
| Classes | Digits 0–9 |

## Model

The final model is a CNN with convolutional feature-extraction layers, batch normalization, max-pooling, dropout, a fully connected layer, and a ten-class softmax output. The model accepts images with shape **28 × 28 × 1**.

## Recorded evaluation results

The CNN evaluation run recorded the following results on the 10,000-image MNIST test set:

| Metric | Recorded result |
|---|---:|
| Test accuracy | **99.40%** |
| Test loss | **0.0175** |
| Validation accuracy (best) | **99.17%** |
| Training accuracy (best) | **99.51%** |
| Macro precision | **99.41%** |
| Macro recall | **99.39%** |
| Macro F1-score | **99.39%** |
| Weighted F1-score | **99.40%** |

These values are from the recorded CNN run. Earlier ANN experiments in the notebook are development history and should not be confused with the final CNN results.

## Technology stack

- Python
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib
- Scikit-learn
- Gradio
- Pillow
- Google Colab / Jupyter Notebook

## How to explore the project

1. Open the Jupyter notebook in Google Colab or Jupyter.
2. Run the notebook cells in order to load the dataset, preprocess images, build and train the CNN, and evaluate its performance.
3. Run the Gradio interface cells to draw a digit or upload an image and view the prediction.

The notebook and source files will contain the exact environment setup and execution details for this project.

## Project deliverables

The repository is intended to contain:

- Jupyter Notebook (.ipynb)
- Python source file (.py)
- Trained Keras model (.keras)
- Project report (Word and PDF)
- Abstract and synopsis
- PowerPoint presentation
- Screenshots of the dataset, training, evaluation, and predictions

## Disclaimer

This is an educational project demonstrating handwritten digit classification on the MNIST dataset. Performance on user-provided handwriting may vary depending on writing style, image quality, and similarity to MNIST examples.
