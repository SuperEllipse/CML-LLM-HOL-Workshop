# Using a Large Language Model with own Data to provide Contextual Responses using Langchain Framework

## Objective
Here we use the Langchain Framework for prompting: There are two notebooks here: 
-  **Tutorial 1**: Chain on Thought and Logical Reasoning Prompts: We use some basic prompting techniques using long chain. See the note book [Intro_langchain-basic.ipynb](Intro_langchan-basic.ipynb) 
-  **Tutorial 2**: Contextualizing Model with own data.   
We use the Langchain framework and a Retrieval Augmented Generation ( RAG) architecture to make a Large Language Model more contextual. The idea is to make the Language model more context aware on a specific dataset. To do this, we choose a downloaded Sherlock Holmes book that is available freely as a part of Project Gutenberg. The book is then used to augment the Large language model with greater context to answer questions specific to cases solved by Sherlock holmes. This approach is a fun take and uses the same approach as the CML AMP [here](https://github.com/cloudera/CML_AMP_LLM_Chatbot_Augmented_with_Enterprise_Data)

## Highlights of the approaches demonstrated here  : 
- Chain of Thought and Logical Reasoning of Prompts
- Augmentation of a Large Language Model using contextual data ( e.g. owned documents) 
- Using Langchain to work with document data for prompt generation
- Using an opensource Vector Database

## Notes : 
Tutorial 1 Model Used : [flan-t5-large](https://huggingface.co/google/flan-t5-large)  
Tutorial 2 Model Used : [Vicuna-7b](https://huggingface.co/eachadea/vicuna-7b-1.1)  
RAG Architecture: [paper](https://arxiv.org/abs/2005.11401)  
Sherlock Holmes book (Project Gutenberg) : [here](https://www.gutenberg.org/ebooks/1661)