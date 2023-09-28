# Single Shot/ Basic Prompts on an Open source Model 

## Objectives
The accompanying notebook demonstrates how to download a pre-trained model from Huggingface hub for inferencing. Along the we will learn: 
- Setting up / Checking availability of GPUs and CUDA libraries
- How to download a Tokenizer / Models using right classes from Transformers library
- How to decode the outputs as well as learn the use of the hyperparameters for text generation
- Finally we will use torch framework to ensure that the GPU memory is released for other sessions

## Model Specifications used: 
Model Name : Bloom1B7  
Model Type : Generative  
Model Card : [here](https://huggingface.co/bigscience/bloom-1b7)