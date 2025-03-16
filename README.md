# Lo-Bot - Law Chatbot

Lo-Bot is a **Retrieval-Augmented Generation (RAG) chatbot** designed to assist with legal queries. It utilizes **DeepSeek**, **LangChain**, and **FAISS** for document retrieval and Mistral for generating responses. The chatbot enables users to query legal documents efficiently.

## 🚀 Features
- **RAG-based** chatbot for legal document retrieval
- **DeepSeek & LangChain** for intelligent querying
- **FAISS vector store** for efficient document search
- **Streamlit** for an interactive user interface

## 📂 Project Structure
```
📦 rag-with-deepseek
 ┣ 📂 vectorstore
 ┃ ┗ 📂 db_faiss
 ┃ ┃ ┣ 📜 index.faiss
 ┃ ┃ ┗ 📜 index.pkl
 ┣ 📜 frontend.py          # Streamlit UI
 ┣ 📜 rag_pipeline.py      # RAG pipeline logic
 ┣ 📜 vector_database.py   # FAISS vector store handling
 ┣ 📜 universal_declaration_of_human_rights.pdf  # Sample legal doc
 ┣ 📜 Pipfile             # Python dependencies
 ┣ 📜 Pipfile.lock        # Dependency lock file
 ┣ 📜 .gitignore          # Ignored files (includes .env)
 ┗ 📜 .env                # Environment variables (DO NOT SHARE)
```

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/HayaAmeerHussain/Lo-Bot---Law-Chatbot-.git
cd Lo-Bot---Law-Chatbot
```

### 2️⃣ Install Dependencies
Using Pipenv:
```sh
pipenv install
```
Or, using pip:
```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file with required API keys:
```
API_KEY=your_api_key_here
MODEL_PATH=your_model_path_here
```

### 4️⃣ Run the Chatbot
```sh
streamlit run frontend.py
```

## 🛠 Future Improvements
- Support for multiple legal documents
- Integration with additional LLMs
- Improved document ranking and retrieval

## 🤝 Contributing
Feel free to fork this repo, open issues, or submit pull requests!

## 📜 License
This project is licensed under the **MIT License**.

---
Developed by **Haya Ameer Hussain** 👩‍💻 🚀
