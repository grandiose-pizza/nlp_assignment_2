# NLP Challenge for Core42 AI Modelling team

## Goal
Build a multi class image classification model using any framework(PyTorch, Keras, etc..) and deploy via a REST API

## Format Requirements
- Fork or clone this repo
- Maintain the directory structure given for the project
- Use Python 3.7+
- If you need additional imports specify them in `requirements.txt`

## Model Requirements
- Model should be trained on the given dataset.
- Create a model artifact and save it under `/models`.
- Report accuracy on `test`.


## API Requirements
- Serve the model as a REST API using FastAPI
- Be able to use CURL to send in text input and return the prediction.

## Data
The dataset you will be using contains 10 classes of apparels. You need to train basic image classification model which will classify given text into these 10 classes categories. You can find the dataset and details data format and labels can be found [here](https://huggingface.co/datasets/fashion_mnist)

Dataset contains two splits `train` and `test`.


## Submission
Timebox this challenge to 8-10 hours. After completing the assignment, please compress whole repo and send it.
