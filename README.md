# RAG System using LlamaIndex and LanceDB
This notebook demonstrates how to build a Retrieval-Augmented Generation (RAG) system for question answering on the jp-handbook-full.pdf document using:

- LlamaIndex for document processing and querying
- LanceDB as the vector store

# Steps 

### 1. Install Required Dependencies
##### Notes:
    - Inside VS Code, I have to install the Jupyter Notebook extension, it installs a kernel and I have to choose Python environment instead of Jupyiter server.
    - I also signed up for a Google Gemini API as we will use Gemini here.
    - Installation of required libraries. 
    - It took few seconds to install these dependencies.

### 2. Import Libraries
##### Notes:
    - Import of required libraries. 
    - It took few seconds to install these dependencies.

### 3. Load and Process the PDF Document
##### Notes:
    - The PDF is 2.7 MB in size with 132 pages.
    - After the run, it says "Loaded 132 document(s)". Looks like the default chunking is per page. 
    - It took around 7s to run this step. 
    - Question? Where did it load the chunks? In-memory perhaps?

### 4. Parse the Document into Nodes
##### Notes:
    - After the run, it says "Document split into 132 nodes". It appears default node is a page in this case. 
    - It took 0.4s to finish. 

### 5. Set Up LanceDB Vector Store
##### Notes:

### 6. Create a Query Engine
##### Notes:

### 7. Ask Questions
##### Notes:

### 8. Multiple Q&A
##### Notes:

### 9. Interactive Q&A
##### Notes:

### 10. Conclusion
##### Notes:

## License

[MIT](https://choosealicense.com/licenses/mit/)
