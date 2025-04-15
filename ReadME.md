ReadME.md

# Fashion-MNIST CNN Classifier

This project uses a **Convolutional Neural Network (CNN)** to classify grayscale clothing images from the Fashion-MNIST dataset into one of 10 categories.

## Model Summary

The model was trained on 60,000 labeled images and tested on 10,000 unseen images. It predicts one of the following categories: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle, Boot.


## Tech Stack

- Python3
- TensorFlow / Keras
- Matplotlib (for visualizations)
- Google Colab / Jupyter

## Model Architecture

- **Conv2D**: 32 filters, 3x3 kernel, ReLU + BatchNormalization + MaxPooling
- **Conv2D**: 64 filters, 3x3 kernel, ReLU + MaxPooling
- **Flatten**
- **Dense Layer**: 64 neurons with Dropout
- **Output Layer**: 10 neurons with Softmax


## Running the Code

To run locally:

```bash 
pip3 install -r requirements.txt
python3 fashion-mnist-cnn.py

or...

Using Google Collab:

Open fashion-mnist-cnn.pynb in google collab


## After Training:

After the 10 epochs have run and the model has been successfully trained you can then change the  value for "index" in PT2_Predictions which corresponds to images in the data set that the model will then predict by showing you the action and predicted category.  
