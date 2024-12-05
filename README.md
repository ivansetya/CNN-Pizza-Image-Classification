# CNN-Pizza-Image-Classification

This repository contains a Convolutional Neural Network (CNN) for pizza image classification. Below is the structure of the project:

submission<br>
├───tfjs_model<br>
  | ├───group1-shard1of2.bin<br>
  | ├───group1-shard2of2.bin<br>
  | └───model.json<br>
├───tflite<br>
  | └───pizza_model.tflite<br>
├───saved_model<br>
  | └───pizza_model_savedmodel.h5<br>
├───notebook.ipynb<br>
├───README.md<br>
└───requirements.txt<br>

## Description

- **tfjs_model**: TensorFlow.js format of the trained model, including shards and model metadata.
- **tflite**: TensorFlow Lite format of the trained model for mobile deployment.
- **saved_model**: Saved model in `.h5` format for further use in TensorFlow.
- **notebook.ipynb**: Jupyter notebook containing the training and evaluation process.
- **README.md**: Documentation and overview of the project.
- **requirements.txt**: List of required Python dependencies for running the project.

