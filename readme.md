#  GenAI CML Workshop / Hands-on-Lab

## Content Synopsis



## 1 Objective: 
     The purpose of this Workshop is to enable existing or prospective customers to experience how they can use Cloudera Machine Learning(CML) for developing Generative AI Applications. This workshop will focus on the application uses cases around using Large Language Models popularly abbreviated as LLMs.   
            CML offers prototypes called as AMPs ( Applied Machine Learning Prototypes) that can be used to quickly spinoff LLL Applications. Please refer to references for more details on this topic
 
## 2 Getting Started: 
    Most LLM Models will employ some GPU compute and hence it is essential that at this point you have access to GPU Hardware. If you are on CML Public cloud the best way to get started is to provision a new Workspace and set it up to include a GPU. For almost all the exercises here i use the basic V100 GPU. Here i use mostly Amazon Web Services (AWS) to set up necessary compute but it really is not necessary to use AWS. You can set up any other Hyperscaler to work with CML as well. Refer to CML Public cloud documentation on the web if necessary.

### 2.1 Setting up a CML Workspace for GPU
    In order to work with GPUs your CML Workspace must be provisioned with GPU Compute and you will be needing to also use GPU runtimes. Couple of things may trip you up when you are trying to provision GPU infrastructure : 
    - The Cloud Provider may not have a GPU instance in the region that you are requesting the GPU. In this case you need to check the GPU availablity for that region. The best way to do that in case of AWS is to login to your AWS Account and check the available GPUs for the region in which you are creating the Workspace. Refer to the following
    - INSERT PICTURE of AWS REGION WITH GPU INSTANCES
    - INSERT PICTURE of GPU SELECTION ON CML WORKSPACE. 

    Make sure that you are either using a GPU provisioned workspace or are able to create a workspace with the GPU instance successfully before proceeding further with this workshop/ demo

### Accessing Large Language Models and Datasets
    In all the exercises we will be accessing Huggingface hub as a source for the models. In order to do this it is a good idea to create an account on hugging face because in some cases hugging face may require a user access token to access Hugging face. Here are some somethings to do : 
    1. Create a new account on Hugging face if you do not have one. If you are a cloudera employee you can also use a corporate account ( cloudera account to login to Hugging face now)
    2. Setup an Access token on Hugging Face

### Setting up libraries 
    Besides using ML Libraries ( e.g. Pandas , Numpy etc ) 

## Exercises on using LLMs on CML 
---
Clicking on each leads you to a folder with a notebook and/or code artefacts folder
1. **Prompting LLMs :** Downloading and Prompting a pretrained LLM from Hugging on CML. 
2. **Advanced Prompting :** Work with a pretrained model to set up advanced prompting using Langchain Framework
3. **Chain-of-thought Prompting :** Work with a pre-trained model towards a chain of thought style prompts ( TO BE DEVELOPED)
4. **Deploying Models in CML using CML API** : Use CML API to deploy a model as an API Endpoint and test the model in a command line or jupyter notebook
5. **Domain Adaption for Finance** : Use a custom Dataset to demonstrate fine tuning using LoRA adapters on a financial Dataset
6. **Measuring Model Preformance** : Benchmark a pre-trained model and compare the model performance against the finetuned model in step 5. 
7. **Developing and Deploying User Applications**: 
Use Gradio to build and deploy AI applications 
8. **Distributing Fine-tuning Workloads on GPU** : Distributing the finetuning workloads with DASK on CML 