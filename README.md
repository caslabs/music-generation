# music-generation
Apply AI Group 24 - Music Generation using deep learning methods

https://caslabs.ai/music-generation

This repo is a submission for our music generation project in Apply AI. To run our code, you can use Google Colab, a free online platform that provides Jupyter notebooks with free access to GPUs. If you have any questions or feedback, please feel free to contact us.

# Music Transformer AI: A Comprehensive Guide

This repository contains the source code and documentation for our Music Transformer AI project, aimed at generating music using deep learning techniques. The project is built upon a transformer-based architecture for musical generation and is trained on the Maestro v3 dataset. We have also included supplementary Jupyter notebooks to provide an in-depth understanding of our thought process and methodology.

For a detailed explanation of our project, please refer to the accompanying Jupyter notebook: Exploration_and_Analysis.ipynb.

Repository Structure
Below is a brief overview of the repository's structure and the purpose of each folder and file:

`/models`
This folder contains the transformer model used for musical generation. The model is designed to handle MIDI data and generate new music based on the learned patterns and structures from the training dataset.

`/data-viz`
This folder contains the Jupyter notebooks dedicated to data visualization and analysis:

`metadata-maestro.ipynb`: This notebook provides detailed information about the Maestro v3 dataset, including an overview of the dataset, its features, and the distribution of the data.
`/data_preprocessing`
In this folder, you will find Jupyter notebooks that cover the data preprocessing steps necessary for model training:

`balance_MIDI.ipynb`: This notebook explains the process of selecting and balancing the MIDI dataset utilized for training our transformer model.

`Midi2Tensor.ipynb`: This notebook details the conversion of MIDI files into a suitable representation (tensors) that can be fed into the transformer model for training.


We hope that this documentation provides a clear understanding of our project and its components. Feel free to explore the repository and utilize the resources provided.
