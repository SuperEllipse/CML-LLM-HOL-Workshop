# Fine Tuning a LLM for Finance Domain using LoRA Adapters on a Custom Dataset
## Objective: 
In this use case we will use adapt a large language Model to financial domain by fine tuning the model to a custom dataset. The idea is to make the model
more context aware to financial data and serve as a helpful tool for the task of providing summaries of financial documents that contains both textual and 
numerical information. To get an idea of the different possible domains that you can adapt LLM Use cases to, please refer to the picture below  


## Description:
Using LoRA adapters is now a popular technique for tuning large language models. This method is called as Performance Efficient Fine Tuning approach since 
it allows us to train a smaller set of model weights and still achieve equivalent model performance. A detailed expose on the LoRA adapters can be read 
in this [paper](https://arxiv.org/abs/2106.09685).

## Dataset for Finetuning:
For finetuning we use the FINDSum Dataset, that has been created using 1000s of Annual reports. Details of the Dataset is available [here](https://github.com/StevenLau6/FINDSum)

## Architecture Overview:
In this example of domain adaptation, we use store the dataset in an s3 bucket and load the dataset using s3 libraries and Transformer libraries.for larger models S3 buckets
can be considered for storing hte model in order to keep the CML Containers lightweight. The picture below represents a high level architecture of the 
use case.  

