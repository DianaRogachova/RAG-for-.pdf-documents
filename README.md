In this notebook we will explore the **Retrieval Augmentated Generation (RAG)** approach to use with a Large Language Model (LLM) to answer questions based on a reference file. In our case, we will use a pdf file that model has not seen before, and test its ability to generate responces based on the content of the pdf file. 

This notebook is based on a template hosted on [GitHub](https://www.youtube.com/watch?v=0xyXYHMrAP0&t=1173s) and tutorial hosted on [YouTube](https://www.youtube.com/watch?v=0xyXYHMrAP0&t=1173s) by James Calam. We have customized portions of the code to fit our particular needs.

In this project we will use Flan T5 XL for an LLM, MimiLM as an embedding model and Pinecone for vector database. All code is executed on SageMaker, using S3 as the storage for the reference file.  
