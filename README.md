# Neural-Network-Classification-Casting-Defect-Detection
Python code extracted from a Jupyter notebook academic submission, covering neural network classification, hyperparameter tuning, and image-based defect detection using MLPs and CNNs.
This repository contains cleaned Python code extracted from a Jupyter notebook academic submission (ENG2006 Coursework 2).
The code is presented as a single, linear Python script and represents a jumble of notebook cells reordered and stripped of all automatic feedback, marking cells, and checker logic.

The original work was developed in a Jupyter environment for assessment purposes; this repository serves as a reference implementation and portfolio archive, not a polished software package.

Contents Overview

The code includes **two** main components:

**1. Neural Network Classification of 2D Data**

--

Loading and visualisation of labelled 2D point data

Train / validation / test splitting

Fully connected neural network (TensorFlow / Keras)

Manual hyperparameter grid search:

Number of hidden layers

Number of hidden units

Learning rate

Early stopping with a minimum epoch constraint

Selection and saving of the optimal model (modelOpt)

Test-set evaluation and confusion matrix

Decision-boundary visualisation

--

**2. Casting Defect Image Classification**

--

Image loading using OpenCV (grayscale, resizing)

Dataset construction from industrial casting images

Normalisation and dataset splitting

Feedforward MLP model for image classification

Convolutional Neural Network (CNN) for improved performance

Early stopping and test-set evaluation

Saving trained models

Visualisation of CNN feature maps (activation maps)

Notes on Structure

The script reflects the structure of a Jupyter notebook, not a modular Python package

Cells have been merged sequentially; some variables persist across sections
