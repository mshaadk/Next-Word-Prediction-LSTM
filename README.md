# Next Word Prediction Model using LSTM
This project involves building a next-word prediction model using a Recurrent Neural Network (RNN) with LSTM layers. The model is trained on a text corpus to predict the next word given a sequence of words. The implementation is provided in a Jupyter Notebook, which can be run directly in Google Colab.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Model Details](model-details)
5. [License](#license)
   
## Project Overview
This project demonstrates how to build and train a next-word prediction model using TensorFlow and Keras. The model is trained on a dataset of Sherlock Holmes stories and uses an LSTM network to predict the next word in a sequence.

## Getting Started
To get started, follow these steps:

1. **Open the Project in Google Colab**:

  - You can open the notebook directly in Google Colab by clicking here.
    
2. **Upload the Dataset**:

  - Ensure that you upload the `sherlock-holm.es_stories_plain-text_advs.txt` dataset to the Colab environment. You can use the file upload feature in Colab or mount Google Drive to access the file.

3. **Run the Notebook**:

  - Execute each cell in the notebook to follow the entire process from data preprocessing to training the model and generating predictions.

## Usage
Once the notebook is running, you can follow these steps to use the model:

1. **Training the Model**:

  - The notebook includes code to load the dataset, preprocess it, build and train the LSTM model. Training may take a while depending on your computational resources.

2. **Generating Predictions**:

  - After training, you can use the model to generate the next word in a given sequence. Modify the seed_text variable in the notebook to test different input sequences.

## Model Details
- **Architecture**: LSTM-based neural network
- **Layers**:
  - Embedding Layer
  - LSTM Layer
  - Dense Layer (Softmax activation)
- **Training Parameters**:
  - Loss Function: Categorical Crossentropy
  - Optimizer: Adam
  - Epochs: 100

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
