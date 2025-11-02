# Ollama-pdf-reader-and-chatbot
📄 LangChain PDF Chatbot
This project is an AI-powered PDF Assistant built with LangChain, OpenAI, and Streamlit. It allows users to upload a PDF file, extract its content, and interact with it through natural language queries. The model understands context and provides intelligent answers based on the document.

🚀 Features


🧠 AI Chat with PDF – Ask questions about any uploaded PDF.


⚙️ LangChain Integration – Efficient text splitting, embeddings, and vector search.


🔐 Environment Variables Support – API key management using .env for security.


💬 Streamlit UI – Clean and simple user interface for smooth interaction.


⚡ Fast Search – Uses FAISS or Chroma vector databases for quick retrieval.



🧰 Tech Stack


Python 3.10+


Streamlit – For front-end app deployment


LangChain – For document processing and conversational context


OpenAI API – For GPT-based text generation


PyPDF2 / pdfplumber – For PDF text extraction


dotenv – For managing environment variables



📦 Installation


Clone the repository:
git clone https://github.com/yourusername/langchain-pdf-chatbot.git
cd langchain-pdf-chatbot



Create and activate a virtual environment:
python -m venv venv
venv\Scripts\activate      # On Windows
source venv/bin/activate   # On Mac/Linux



Install dependencies:
pip install -r requirements.txt



Set your OpenAI API key in a .env file:
OPENAI_API_KEY=your_api_key_here




▶️ Usage
Run the Streamlit app:
streamlit run main.py

Then open the provided local URL in your browser.

📁 Project Structure
📦 langchain-pdf-chatbot
 ┣ 📄 main.py
 ┣ 📄 requirements.txt
 ┣ 📄 .env
 ┣ 📂 venv/
 ┣ 📄 README.md


⚠️ Troubleshooting
If you encounter any LangChain import errors, make sure to install the latest langchain-openai package:
pip install -U langchain-openai

If PDF decryption fails:
pip install cryptography>=3.1


🧑‍💻 Author
Developed by Ali Mashaghi
Student • Programmer • AI Developer

Do you want me to make it sound more GitHub-professional (like with badges, emojis, and deployment section), or keep it minimal and clean for portfolio use?
