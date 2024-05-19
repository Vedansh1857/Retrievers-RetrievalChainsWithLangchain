# Retrievers-RetrievalChainsWithLangchain

### 1. Ingested the data(Attention is all you need PDF) using PyPDFLoader.
### 2. Split it into chunks using langchain text splitters.
### 3. Used OpenAIEmbeddings for vector embeddings.
### 4. Used FAISS DB to store those vectors.
### 5. Created a document chain using langchain's create_stuff_documents_chain.
### 6. Created retriever on top of the FAISS database.
### 7. Finally created retrieval chain & invoked it with a query.
