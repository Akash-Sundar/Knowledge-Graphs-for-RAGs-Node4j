# Knowledge Graphs for Retrieval-Augmented Generation (RAG) with Neo4j  

This repository explores the integration of knowledge graphs (KGs) into Retrieval-Augmented Generation (RAG) pipelines, utilizing Neo4j for graph management and OpenAI LLMs for natural language understanding and generation. Through a series of Jupyter notebooks, we incrementally build and expand a knowledge graph, preparing it for RAG-based interactions.  

## Notebooks  

Below is the sequence in which the notebooks should be executed to understand and implement the concepts effectively:  

1. **`query_with_cypher`**  
   Learn the basics of querying knowledge graphs using Cypher, Neo4j's query language.  

2. **`prep_text_for_RAG`**  
   Prepare text data for ingestion into a RAG pipeline, including preprocessing and structuring.  

3. **`construct_kg_from_text`**  
   Construct a knowledge graph from textual data, defining nodes and relationships.  

4. **`add_relationships_to_kg`**  
   Enrich the knowledge graph by adding meaningful relationships between existing nodes.  

5. **`expand_the_kg`**  
   Expand the knowledge graph by incorporating new data and connecting it to existing nodes.  

6. **`chat_with_kg`**  
   Interact with the knowledge graph using OpenAI's LLMs, enabling a conversational interface for querying and retrieving information.  

## Prerequisites  

- **Neo4j**: Installed and running locally or on a cloud instance.  
- **Python 3.8+**: Ensure your environment includes necessary Python libraries such as `neo4j`, `openai`, and `pandas`.  
- **Jupyter Notebook**: For running the provided notebooks.  


## Project Goals
* Introduce and implement the use of knowledge graphs in RAG pipelines.
* Demonstrate the power of Cypher for querying and managing knowledge graphs.
* Showcase how to use OpenAI LLMs for conversational interactions with a knowledge graph.
