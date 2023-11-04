# Transcription Factor Binding Site Prediction 

This repository contains a Keras implementation of a binding prediction model that incorporates convolutional layers, LSTM, and a custom self-attention mechanism.

## Description

The model aims to predict binding affinities based on sequential input data. It uses a combination of 2D convolutional layers to extract features from the input sequence, followed by bidirectional LSTM layers to capture long-range dependencies, and a custom self-attention layer to capture various dependencies within the sequence.

## Installation

To install the required packages, you will need Python 3.6 or later and pip. It is recommended to create a virtual environment before installing the dependencies to avoid conflicts with other packages.

```bash
# Create a virtual environment
python -m venv myenv

# Activate the virtual environment
# On Windows:
myenv\Scripts\activate
# On Unix or MacOS:
source myenv/bin/activate

# Install the package
pip install tensorflow
pip install keras
```

This project is open source and available under the MIT License.
