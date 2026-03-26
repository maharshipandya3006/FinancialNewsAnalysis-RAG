# Built by Maharshi Pandya

# FinancialNewsAnalysis-RAG
Built a financial news analysis tool using Retrieval-Augmented Generation (RAG), leveraging LangChain, FAISS vector search, and OpenAI APIs to extract, embed, and query insights from live article URLs with source-backed responses.

Tech Stack - Python, LangChain, OpenAI, FAISS, Streamlit

Features included:
Chat with financial news articles via URLs
Retrieval-Augmented Generation (RAG) pipeline
FAISS vector search for efficient retrieval
Source-based answers for transparency
Streamlit interactive UI

▶️ Run
pip install -r requirements.txt

streamlit run main.py

Working:
-->The web app will open in your browser.

-->On the sidebar, you can input URLs directly.

-->Initiate the data loading and processing by clicking "Process URLs."

-->Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.


-->The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.

-->The FAISS index will be saved in a local file path in pickle format for future use.
-->One can now ask a question and get the answer based on those news articles
