## Research Paper Management System RAG Chatbot
Uses MongoDB Atlas vector search and Gemini to create a chatbot to interact with private research documents in universities!

### Setup
1. Put Gemni API and your atlas connection string in a ```.env``` file
2. Use ```create-index.js``` and ```create-embeddings.js``` to create a vector index for your db and convert documents to vector embeddings.
3. Execute ```node app.js ```
