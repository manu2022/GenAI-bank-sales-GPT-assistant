This is a dump project for generative ai to simulate a sales GPT bank assistant.

It uses some laoders, such as pdf loader, audio file to text rransformers and webscrapper to ingest content into an index in Pinecone db.

The app uses langchain with agent as Ai orchestrator and different tools assigned, one of them using RAG and semantic search

A GenAI assitant to empower the bank sales, it uses a langchan agent orchestrator with different tools assigned to eat and executes the right one depending on the question. The main tool uses RAG with product and services data, so by using semantic search the LLM will finally suggest an assist the user with the products, therefore the real persons will have more time to deal with the inquieries and requests. In addition, it has a mechanism to ingest data into the index in PDF, webs rapping, or audio files, using hugging face models for speech2text

![image](https://github.com/manu2022/GenAI-bank-sales-GPT-assistant/assets/91486311/bc9764b0-b9a0-4159-8f19-dae7f68cb8b3)
