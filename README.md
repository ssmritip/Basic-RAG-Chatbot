# Basic-RAG-Chatbot
A basic **Retrieval-Augmented Generation (RAG)** chatbot that combines document retrieval and generative AI for accurate responses. It fetches relevant documents from URLs or PDFs and uses those as context to generate responses with a language model.

### Features
- Loads content from URLs or PDFs.
- Uses Google GenAI for embeddings and Groq for LLM execution.
- Powered by LangChain, FAISS, and Gradio.

### Installation
1. Clone the repository:
`git clone https://github.com/ssmritip/Basic-RAG-Chatbot.git`
2. Create a virtual environment and install dependencies:
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```
3. Set up your API keys in a `.env` file:
```
GOOGLE_GENAI_API_KEY=<your_google_genai_api_key>
LANGCHAIN_API_KEY=<your_langchain_api_key>
GROQ_API_KEY=<your_groq_api_key>
```

### Usage
Run the chatbot with Gradio: 
`
python app.py
`
### Hugging Face Hosted Chatbot
You can access the deployed chatbot directly on Hugging Face Spaces:

[**Click here to try the chatbot on Hugging Face**](https://huggingface.co/spaces/ssmritip/basic_rag)

---