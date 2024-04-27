# MNIST Digit Prediction API using FastAPI

This project implements a FastAPI application that predicts handwritten digits from images using a pre-trained MNIST model. Users can upload an image containing a handwritten digit, and the API will return the predicted digit.

## Features

- FastAPI application with a `/predict` endpoint to handle image uploads and return predictions
- Model loading and prediction functions
- Image preprocessing for resizing and converting to grayscale
- Supports various image formats (e.g., PNG, JPEG)

## Getting Started

### Prerequisites

- Python 3.6 or higher
- TensorFlow 2.x
- FastAPI
- Pillow (PIL) library

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/mnist-fastapi.git
