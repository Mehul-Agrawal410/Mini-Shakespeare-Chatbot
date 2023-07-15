# Mini-Shakespeare-Chatbot

This repository contains a transformer-based decoder-only chatbot trained on a mini Shakespeare dataset, utilizing character-based tokens. The model leverages advanced techniques to enhance its conversational capabilities and context awareness.

## Dataset
The `input.txt` file contains an approximately 1.1 Million character dataset used for training the chatbot model. It serves as the basis for generating coherent responses.

## Outputs
The `outputs.txt` file includes the model's 10,000-token output based on a context of zeros. Please note that due to limited computational resources, the generated outputs may not be optimal. However, by training on a GPU with increased batch size, block size, embedding size, and utilizing CUDA acceleration, superior results can be achieved.

## Usage
To run the chatbot model and generate responses, follow these steps:
1. Execute ``GPTbot.ipynb`` on google colab or locally with PyTorch and Jupyter installed.
2. Customize the training parameters and model architecture as needed.
3. Experiment with different datasets and preprocessing techniques to enhance performance.

## References
1. [Video: Transformer-based Chatbot](https://youtu.be/kCc8FmEb1nY)
2. [Paper: Attention Is All You Need](https://arxiv.org/abs/1706.03762)
