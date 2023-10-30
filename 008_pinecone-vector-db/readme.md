# Pinecone For Semantic Search In CML
In CML, use Pinecone for Semantic Search to retrieve similar documents from a user question. This Jupyter Notebook demonstrates simply how to leverage Pinecone using the sentence transformers library from Hugging Face and the embedding model `all-mpnet-base-v2`.

## Instructions
1. Create an account with Pinecone at https://app.pinecone.io/?sessionType=signup
2. Copy down environmment and API key (if you are using free tier it is `gcp-starter`)
3. Load documents into `/data` or use the ones provided.
4. Execute `PineconeForSemanticSearch.ipynb` and customize the question relevant to the documents loaded into the vector DB.
