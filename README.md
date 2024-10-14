# AI-Parameter-Playground

Welcome to the AI-Parameter-Playground repository! This repository provides a comprehensive guide to creating an AI class using an API key, exploring various parameters, and understanding their effects on model behavior.

## Table of Contents
- Introduction
- AI Class
- Usage Examples
- Model Differences
- Top_p Parameter
- Contributing
- License

## Introduction
This repository demonstrates how to create an AI class with various parameters such as model type, system role, max_tokens, top_p, and temperature. It includes examples of how to use the class, highlights differences between models, and explains the top_p parameter in detail.

## AI Class
The `class_version.py` file contains the implementation of the AI class. The class has the following parameters:
- `model_type`: Specifies the type of model to use.
- `system_role`: Defines the role of the system (assistant, professor, friend, celebrity, doctor etc..).
- `max_tokens`: Sets the maximum number of tokens for the response.
- `top_p`: Controls the diversity of the generated text.
- `temperature`: Adjusts the randomness of the generated text.

## Usage Examples
The `LLM_Examples.ipynb` file provides examples of how to use the AI class. It demonstrates different ways to initialize the class and generate responses based on various parameters.

## Model Differences
The `Different_Models.ipynb` file highlights the differences between models, top_p, and temperature. It randomly chooses between hundreds of possible parameter combinations and shows the variation in the results.

## Top_p Parameter
The `top_p.ipynb` file explains the top_p parameter. It includes a detailed explanation of the concept along with examples of different models' responses based on varying top_p values, helping you understand its impact on text generation.

## Contributing
We welcome contributions to this repository! If you have any suggestions, improvements, or new examples, please feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
