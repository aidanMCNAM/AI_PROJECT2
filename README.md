# AI_PROJECT2
Using Neural Networks to study healthy brains vs brains in danger.
This project implements a Convolutional Neural Network (CNN) for classifying brain MRI scans into four categories:

glioma

meningioma

pituitary

notumor (healthy)

For the primary research objective, the four-class output is also mapped into a binary classification task:

Healthy: notumor

Unhealthy: glioma, meningioma, pituitary

The model is built with PyTorch and includes full training, validation, testing, and binary evaluation logic.

Python 3.10 or later is recommended.
pip install -r requirements.txt

To create and activate a virtual environment:
python -m venv AIProject
source AIProject/bin/activate

Running the Model
Execute the training and evaluation script from the repository root:
python train_brain_cnn_pytorch.py
