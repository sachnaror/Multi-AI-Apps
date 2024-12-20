<a target="_blank" href="https://lightning.ai/akshay-ddods/studios/rag-using-llama-3-3-by-meta-ai">
  <img src="https://pl-bolts-doc-images.s3.us-east-2.amazonaws.com/app-2/studio-badge.svg" alt="Open In Studio"/>
</a>

# LLama3.3-RAG application

This project leverages a locally Llama 3.3 to build a RAG application to **chat with your docs** and Streamlit to build the UI.


## Installation and setup

**Setup Ollama**:
   ```bash
   # setup ollama on linux
   curl -fsSL https://ollama.com/install.sh | sh
   # pull llama 3.3:70B
   ollama pull llama3.3
   ```
**Setup Qdrant VectorDB**
   ```bash
   docker run -p 6333:6333 -p 6334:6334 \
   -v $(pwd)/qdrant_storage:/qdrant/storage:z \
   qdrant/qdrant
   ```

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama llama-index-vector-stores-qdrant
   ```


---
![Alt Text](./resources/image.png)

---

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
