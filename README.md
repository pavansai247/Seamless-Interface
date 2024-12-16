Title: A Seamless Interface for Multi-Application Integration 

  

1. Introduction 

  

In today's fast-paced world, keeping up with current events and extracting useful information from diverse news sources is challenging. Researchers, journalists, and professionals often face difficulties in collecting, processing, and analyzing large volumes of news articles efficiently. Manual processes are time-consuming, error-prone, and limit the ability to extract insights from vast datasets quickly. 

In recent years, Retrieval-Augmented Generation (RAG) has become a breakthrough technique in AI, combining the power of large language models with external knowledge retrieval systems. This project aims to integrate different applications into a single user-friendly interface. This platform is useful for your EDUNET Trainers, using this Interface trainers can explain the Generative Models like RAG, GAN, Transformers. They can give the demo on this RAG how the data is Retrieval and demo on GAN Models how the images are generated, how it works and how to create their own models using the Api's. Then the students can easily understand how the different model gives the output. The project will enable seamless interaction and increased efficiency for users across different sectors. 

 

 

Task 1: News Research Tool 

Overview 

From news websites, blogs, and social media platforms, the amount of content available online is overwhelming. According to recent reports, over 2 million articles are published every day. For professionals who need to stay updated, this constant stream of data becomes hard to navigate. 

Traditionally, news research is done manually or with simple keyword-based search engines. These methods often fail to provide relevant results because they lack the ability to understand the context and nuances of the content. Current solutions also struggle with efficiently extracting insights from large volumes of text, and they lack customization based on specific research needs. 

The goal is to implement a Retrieval-Augmented Generation (RAG) pipeline that allows users to interact with semi-structured data in multiple PDF files. The system should extract, chunk, embed, and store the data for efficient retrieval. It will answer user queries and perform comparisons accurately, leveraging the selected LLM model for generating responses. 

 Functional Requirements 

 

Data Ingestion 

Input: PDF files containing semi-structured data. 

Process: 

Extract text and relevant structured information from PDF files. 

Segment data into logical chunks for better granularity. 

Convert chunks into vector embeddings using a pre-trained embedding model. 

Store embeddings in a vector database for efficient similarity-based retrieval. 

 

Ǫuery Handling 

 

Input: User's natural language question. 

Process: 

Convert the user's query into vector embeddings using the same embedding model. 

Perform a similarity search in the vector database to retrieve the most relevant chunks. 

Pass the retrieved chunks to the LLM along with a prompt or agentic context to generate a detailed response. 

 

Comparison Ǫueries 

 

Input: User's query asking for a comparison 

Process: 

Identify and extract the relevant terms or fields to compare across multiple PDF files. 

Retrieve the corresponding chunks from the vector database. 

Process and aggregate data for comparison. 

Generate a structured response (e.g., tabular or bullet-point format). 

 

Response Generation 

 

Input: Relevant information retrieved from the vector database and the user query. 

 

Process: 

Use the LLM with retrieval-augmented prompts to produce responses with exact values and context. 

Ensure factuality by incorporating retrieved data directly into the response. 

 

Example Data: 

 

400 IndiGo flyers stuck in Istanbul for nearly 2 days | India News - Times of India 

BJP veteran LK Advani, 97, admitted to ICU | India News - Times of India 

 

Extract accurate information: 

 

From page 2 get the exact unemployment information based on type of degree input 

From page 6 get the tabular data 

 

Solution: 

 

 "Bot" will utilize AI and machine learning models, including a combination of embeddings for semantic search and language models for text generation. The system will be built using the LangChain framework to provide the following components 

Question Answering Chain: Using a retrieval-augmented generation (RAG) architecture, the tool will generate answers to user queries based on relevant content fetched from the vector store. 

 

 Task 2: Chat with Database Using RAG Pipeline Overview 

The goal is to implement a Retrieval-Augmented Generation (RAG) pipeline that allows users to interact with structured and unstructured data extracted from Database. The system will extract content, instead of writing the queries we can access the data from the database with prompts. Users can query the system for information and receive accurate, context-rich responses generated by a selected LLM. 

 

Functional Requirements 

Data Ingestion 

Input: URLs or list of websites to crawl/scrape. 

Process: 

Connect the target database and Train with the data in the database. 

Extract key data fields, metadata, and textual content. 

Segment content into chunks for better granularity. 

Convert chunks into vector embeddings using a pre-trained embedding model. 

Store embeddings in a vector database with associated metadata for efficient retrieval. 

Ǫuery Handling 

Input: User's natural language question. 

Process: 

Convert the user's query into vector embeddings using the same embedding model. 

Perform a similarity search in the vector database to retrieve the most relevant chunks. 

Pass the retrieved chunks to the LLM along with a prompt or agentic context to generate a detailed response. 

​ 

Response Generation 

Input: Relevant information retrieved from the vector database and the user query. 

Process: 

Use the LLM with retrieval-augmented prompts to produce responses with exact values and context. 

Ensure factuality by incorporating retrieved data directly into the response. 

 

 

Task 3: Video based interaction with the Mode 

 

1.Ǫuery Handling 

Input: User's natural language question. 

Process: 

Convert the user's query into vector embeddings using the same embedding model. 

Perform a similarity search in the vector database to retrieve the most relevant chunks. 

Pass the retrieved chunks to the LLM along with a prompt or agentic context to generate a detailed response.  

GitHUB LINK 
