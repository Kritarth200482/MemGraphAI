# MemGraphAI
AI chatbot with memory and knowledge graph capabilities powered by OpenAI, mem0, and Neo4j.

MemGraphAI is a cutting-edge, memory-enhanced chatbot designed to simulate long-term conversation awareness using a hybrid memory system built on vector embeddings and knowledge graphs. By integrating OpenAI's powerful language models with mem0, Qdrant, and Neo4j, the system can recall previous interactions, reason over structured data, and generate context-aware responses.

🔧 Key Features
💬 Conversational Memory: Leverages mem0 to retrieve relevant past interactions.

🧠 Vector Search: Embeds user queries with OpenAI's text-embedding-3-small model and stores in Qdrant for semantic recall.

🕸️ Knowledge Graph Integration: Uses Neo4j to store and reason over structured facts and concepts.

🧾 System-Prompt Memory Injection: Injects relevant past context into the system prompt to maintain continuity.

🔄 Memory Update Loop: Automatically adds new dialogue turns to memory for future retrieval.


⚙️ Tech Stack
| Component          | Technology                                     |
| ------------------ | ---------------------------------------------- |
| 🧠 LLM             | OpenAI GPT-4.1                                 |
| 📥 Embedding Model | OpenAI `text-embedding-3-small`                |
| 📦 Vector Store    | Qdrant                                         |
| 🔗 Graph Store     | Neo4j                                          |
| 🧩 Memory Layer    | [`mem0`](https://github.com/langchain-ai/mem0) |
| 🐍 Language        | Python                                         |
| 💻 Interface       | CLI (Command Line Interface)                   |


📈 Future Improvements
Streamlit or web frontend
