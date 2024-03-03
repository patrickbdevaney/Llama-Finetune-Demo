# Miami Geography and Ecology Inference Model

This repository contains a Jupyter notebook that runs a fine-tuned version of the Llama-27b model from Hugging Face. The model has been trained on public data concerning the geography of Miami and academic research on the impact of urban activity on the natural environment.

## Model Objective

The goal of this model is to leverage the text-corpus of large language models to provide more transparency and quantifiable knowledge on ecological impact. The focus areas include the Everglades, Biscayne Bay, the Pine Rocklands, and the interleaving flora and fauna of South Florida.

## Getting Started

The Jupyter notebook is designed to be run on Google Colab with a T4 GPU. To get started, you need to have a Hugging Face access token connected to Colab.

1. Connect to a T4 GPU on Google Colab.
2. Connect your Hugging Face account to Colab.
3. Open the Jupyter notebook: Notebook Link
4. Click on 'Run All' to execute all cells in the notebook.

## Notebook Overview

The notebook contains Python Read-Evaluate-Print-Loop (REPL) cells that, when executed in succession, perform the following tasks:

1. Download all required Python packages.
2. Import the necessary libraries.
3. Load the Llama LLM from Hugging Face and a tokenizer into GPU RAM.
4. Run inference on the model and generate a response to the prompt.

The last cell contains a string variable that you can modify to test out different prompts.

## Contributing

Contributions are welcome! 

## License

This Jupyter Notebook file is licensed under the terms of the MIT license.
