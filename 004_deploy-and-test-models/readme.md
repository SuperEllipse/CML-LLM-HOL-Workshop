# Self Hosting and Deploying LLM Models in CML API
## Objective : 
Cloudera Machine Learning provides multiple options for model deployments as an API End point. One option is to use the user interface but if you would like to automate
model deployments, CML APIs are the way to go. In this excercise we will download a Large Language Model and save it locally. This allows us to cache the models for 
subsequent invocations. Next, we will deploy a downloaded model as an CML API.  
Following are the different files in the folder which will help us do so.


## File Artifacts for Model Deployment  

**004_deploy-and-test-models**  
**|--self_hosting_and_deploying_LLMs_in_CML.ipynb**     - Jupyter notebook that downloads and deploys a model          
**|--LLM_inference.py**                                 - Python file with a wrapper function used as API entry point  
**|--model-calling-using-API-endpoint.ipynb**           - Jupyter notebook that calls and tests the deployed model.  


