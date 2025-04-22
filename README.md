# Tweet Summarization with Custom Transformer

## Project Overview

This repository contains the implementation of an abstractive text summarization system specifically designed for tweets using a custom transformer architecture built from scratch. Due to the lack of large-scale tweet summarization datasets, we first trained our models on the CNN/DailyMail dataset, then adapted them for tweet summarization.

## Repository Structure

- **Transformer_training.ipynb**: Contains the complete implementation and training of our custom transformer architecture on the CNN/DailyMail dataset. Includes the model definition, custom tokenization, training loop, and evaluation metrics.

- **Project_20_infer.ipynb**: Contains the final generation code for tweet summarization, applying our trained model to hashtag-based Twitter datasets. This notebook demonstrates how we process tweets and generate summaries for social media content.

- **nlp_app/**: Contains code for the React frontend and Flask backend application, providing an interactive user interface for the summarization system.

## Important Note

The trained model file (`model.pt`) is not included in this repository due to its large size. You can download it from the following link:

[Download model.pt file](https://drive.google.com/file/d/1n39SzC4acCLmrm67llt-dp0U1IDQCj8X/view?usp=drive_link)

After downloading, place it in the appropriate directory within the `nlp_app` folder to enable the web application to function properly.

## Features

- Custom transformer architecture implemented from scratch
- Byte-level BPE tokenization optimized for efficiency
- Advanced decoding strategies with temperature control and repetition penalties
- Web interface for interactive summarization

## Getting Started

1. Clone this repository
2. Download the model file from the link above
3. Install the required dependencies (see requirements in notebooks)
4. Run the notebooks to see the training process and inference examples
5. Follow the instructions in the `nlp_app` directory to set up the web application

## Authors

- Nishad Bagade (MT2024102)
- Rishabh Kumar Singh (MT2024125)
- Kuldeep Chamoli (MT2024081)
- Abhishek Kumar Singh (MT2024006)
