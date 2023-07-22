# Information Extractor using Langchain
 More advanced application of Artificial Intelligence - building a Question Answering (QA) Chatbot that works over documents and provides sources of information for its answers. Our QA Chatbot uses a chain (specifically, the RetrievalQAWithSourcesChain), and leverages it to sift through a collection of documents, extracting relevant information to answer queries. 
The chain sends structured prompts to the underlying language model to generate responses. These prompts are crafted to guide the language model's generation, thereby improving the quality and relevance of the responses. Additionally, the retrieval chain is designed to keep track of the sources of information it retrieves to provide answers, offering the ability to back up its responses with credible references.

1. Scrape online articles and store each article's text content and URL.
2. Use an embedding model to compute embeddings of these documents and store them in Deep Lake, a vector database.
3. Split the article texts into smaller chunks, keeping track of each chunk's source.
4. Utilize RetrievalQAWithSourcesChain to create a chatbot that retrieves answers and tracks their sources.
5. Generate a response to a query using the chain and display the answer along with its sources.

# vector database : Deeplake 

