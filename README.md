# **Flavor Pairing Knowledge Graph with RAG-Supported LLM**

This project leverages a **Knowledge Graph** and **Retrieval-Augmented Generation (RAG)** powered by a **Large Language Model (LLM)** to explore and generate creative flavor pairings. By combining structured knowledge (Neo4j) with the generative capabilities of an LLM (e.g., OpenAI GPT), the system enables innovative and insightful flavor suggestions for culinary applications.

## **Features**
- **Flavor Knowledge Graph**: A graph database (Neo4j) storing relationships between ingredients and their compatibility levels.
- **RAG Framework**: A Retrieval-Augmented Generation workflow integrates structured graph data with LLM responses to enhance contextual relevance.
- **LLM Integration**: Powered by OpenAI, the model generates recipes, pairing ideas, and insights based on graph-queried data.
- **Customizability**: Users can define their own knowledge graph structure and expand it with additional ingredient data.

## **Tech Stack**
- **Neo4j**: Used for storing and querying the Knowledge Graph.
- **OpenAI API**: For generative language capabilities.
- **Python Libraries**:
  - [`llama_index`](https://github.com/jerryjliu/llama_index) for graph and LLM integration.
  - [`dotenv`](https://github.com/theskumar/python-dotenv) for secure environment variable management.
  - Other dependencies: `neo4j`, `openai`.
