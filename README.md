# 🧠 Agentic Thinking RAG AI  
**Watch AI think step-by-step in real-time!**  
A sophisticated RAG system that demonstrates an AI agent's reasoning process using **Agno**, **Gemini**, and **OpenAI**. Observe the complete thought process as the agent analyzes questions, retrieves relevant information, and generates well-reasoned answers.

---

## ✨ Features

### 🔍 Transparent Reasoning
- **Real-time thought display** – Watch the agent’s thinking steps unfold live  
- **Step-by-step reasoning** – See how the agent breaks down complex problems  
- **Side-by-side view** – Reasoning process on left, final answer on right  
- **ReasoningTools integration** – Powered by advanced reasoning capabilities  

### 🌐 Interactive Knowledge Management
- **Dynamic URL addition** – Add web sources on the fly  
- **Persistent vector storage** – LanceDB for efficient retrieval  
- **Session state tracking** – Prevents duplicate URL loading  
- **Default knowledge source** – Pre-loaded with *MCP vs A2A Protocol* article  

### 🚀 Advanced RAG Capabilities
- **Vector search** – OpenAI embeddings for semantic matching  
- **Source attribution** – Complete citations for verification  
- **Multi-model support** – Gemini 2.5 Flash with OpenAI embeddings  
- **Real-time streaming** – Live updates during reasoning  

---

## 🛠️ Prerequisites

### 🔑 Google Gemini API Key
1. Visit [Google AI Studio](https://aistudio.google.com/)  
2. Sign in with your Google account  
3. Go to **API Keys**  
4. Create a new API key  
5. Copy and save it securely  

### 🔑 OpenAI API Key
1. Visit [OpenAI Platform](https://platform.openai.com/)  
2. Log in or create an account  
3. Navigate to **API Keys**  
4. Generate a new secret key  
5. Save it immediately – you won’t see it again!  

---

## 🚀 Installation & Setup

```bash
Step 1: Clone the Repository

git clone https://github.com/SaadKhaquan1211/Agentic-Thinking-RAG-AI.git
cd Agentic-Thinking-RAG-AI

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run the Application
streamlit run rag_reasoning_agent.py
```

💡 How to Use
🎯 Quick Start

- Default Knowledge: MCP vs A2A Protocol article pre-loaded

- Suggested Prompts: “What is MCP?”, “MCP vs A2A”, “Agent Communication”

- Ask Questions: Type your own queries in the input field

🔧 Advanced Usage

- Add Knowledge Sources:

- Use the sidebar to add new URLs

- Documents are processed and embedded automatically

- Session tracking prevents duplicate loading

Observe Reasoning:

- Watch real-time thinking in the left panel

- See final answers with citations in the right panel

- Follow the entire RAG reasoning process transparently

⚙️ How It Works


🏗️ Architecture

- This app implements Agentic RAG, an advanced form of Retrieval-Augmented Generation that includes dynamic decision-making and reasoning:

- Knowledge Base Setup

- Documents loaded from URLs using Agno’s Knowledge class

- Text chunked and embedded via OpenAI embeddings

- Stored in LanceDB for efficient vector retrieval

- Semantic search for contextually relevant information

- Agent Processing Pipeline

- User query triggers a structured reasoning sequence

- ReasoningTools manage each reasoning step

- Knowledge base searched dynamically

- Gemini 2.5 Flash generates comprehensive answers with citations

- Real-time streaming updates the UI

🔄 UI Flow

```text
Enter API Keys → Load Default Knowledge → Add URLs (optional) → Ask Questions
      ↓                ↓                       ↓                 ↓
Key Validation → MCP vs A2A Article → Knowledge Base Expansion → Real-time Reasoning Display

```
🛠️ Technical Stack

- Framework: Agno v2.0

- LLM: Gemini 2.5 Flash

- Embeddings: OpenAI Embedding Model

- Vector Database: LanceDB

- UI: Streamlit

- Reasoning Tools: ReasoningTools for live step-by-step analysis

🌟 Use Cases

- Educational Tool: Learn how AI solves problems

- Research Assistant: Analyze topics with transparent reasoning

- Content Analysis: Understand complex articles step-by-step

- AI Literacy: See how large models think and decide

🤝 Contributing

- Contributions welcome! You can:

- Report bugs or issues

- Suggest new features

- Submit pull requests

- Improve documentation
