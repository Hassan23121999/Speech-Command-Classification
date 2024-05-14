# Speech-Command-Classification
A speech command classification system using a Convolutional Neural Network (CNN) for training and testing audio datasets. This project includes a detailed workflow and GUI for processing and classifying speech commands



# Speech Command Classification

## Project Description
This project provides a speech command classification system using a Convolutional Neural Network (CNN) for training and testing audio datasets. The system imports datasets, processes raw audio files, defines a neural network architecture, and trains, tests, and validates the model. The goal is to classify spoken commands with high accuracy.

## Features
- **Installing Libraries:** Installs essential libraries like PyTorch and TorchAudio.
- **Importing Datasets:** Imports datasets from PyTorch or audio loader packages.
- **Raw Audio File Generation:** Processes raw audio files to generate data points with waveform, sample rate, utterance, speaker ID, and utterance numbers.
- **Formatting Datasets:** Downsamples audio, maps words to labels, introduces a collate function, and swaps sample rates.
- **Defining Network:** Uses a CNN (M5 network architecture) with an optimizer to increase learning rate.
- **Training:** Trains the data subset on every sample of the dataset.
- **Testing:** Tests the data subset on every sample of the dataset.
- **Validation:** Validates the data subset on every sample of the dataset.
- **Training and Testing Network:** Trains the network on datasets with different epochs and records voice commands for one second.

## Flow Chart
The following flow chart illustrates the programming flow for the speech command classification system:

![Speech Command Classification Flow Chart](path/to/your/image.png)

## Installation

### Prerequisites
- Python 3.x
- PyTorch
- TorchAudio
- NumPy
- tkinter

You can install the required packages with pip:
```bash
pip install torch torchaudio numpy tk
```

### Setup
Clone this repository to your local machine:
```bash
git clone https://github.com/Hassan23121999/Speech-Command-Classification.git
cd Speech-Command-Classification
```

## Usage
Run the notebook to execute the speech command classification:
```bash
jupyter notebook "Speech Command Classification Software code.ipynb"
```
Follow the notebook instructions to install libraries, import datasets, process raw audio files, define the network, and train, test, and validate the model.

## Support
For technical support or troubleshooting, please contact the support team via email at:
2016n1770@gmail.com
