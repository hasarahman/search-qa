# Q&A with RAG

This jupyter notebook is an example of using Retrieval Augmented Generation, or RAG, to create a simple q&a system that can answer questions about a given PDF.

Tools used: Open AI Embeddings API, Langchain PyPDFLoader, ChromaDB (to store embeddings).

In this example, I built a q&a system that can answer questions based on my resume. Questions like "is hasan a capable sales engineer?". 

Issues I ran into:
1) Versioning. Jupyter notebook tends to have issues with installing modules on the appropriate directories. You'll see that I had to choose specific versions of modules to get this to run. You can avoid these issues by using Google Cloud's Colab or Vertex AI workbench's managed notebook.
2) ChromaDB is a fantastic DB for lightweight applications, but it isn't built for scale. I suggest looking at Google Cloud Vector Search or AlloyDB AI for vector DBs that can scale.

Resources:
RAG - https://python.langchain.com/docs/use_cases/question_answering/
PyPDFLoader - https://python.langchain.com/docs/modules/data_connection/document_loaders/pdf
Open AI Embeddings API - https://platform.openai.com/docs/guides/embeddings
ChromaDB - https://docs.trychroma.com/getting-started
Google Cloud Vertex AI Workbench Managed Notebook - https://cloud.google.com/vertex-ai/docs/workbench/managed/introduction
Google Cloud Colab (access to GPUs free of charge) - https://colab.research.google.com/?utm_source=scs-index




