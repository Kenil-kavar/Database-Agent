# 🦜 Langchain: Chat with SQL Database  

## 🚀 Overview  
This project is a **Streamlit-based chatbot** that enables seamless interaction with **SQL databases** using **Langchain**. It supports both **SQLite and MySQL** databases, allowing users to query databases in natural language. The chatbot is powered by **Llama3-8b-8192** via **ChatGroq**, ensuring intelligent and contextual responses. AI agents are used for optimized query execution.  

## 🔥 Features  
- **AI-Powered SQL Agent**: Uses AI agents for intelligent query handling.  
- **Interactive Chatbot**: Engage with your database using natural language.  
- **Multi-Database Support**: Connect to **SQLite** (`student.db`) or a **MySQL** database.  
- **Secure Authentication**: Uses a **GROQ API key** for secure AI interactions.  
- **Streamlit UI**: Clean and user-friendly interface with persistent chat history.  
- **Optimized Performance**: Caches database connections for efficiency.  

## 📌 Requirements  
Ensure you have the following installed before running the project:  

- Python 3.8+  
- **Streamlit**  
- **Langchain**  
- **SQLAlchemy**  
- **sqlite3**  
- **mysql-connector-python**  

Install dependencies using:  
```bash  
pip install streamlit langchain sqlalchemy sqlite3 mysql-connector-python  
```  

## 🚀 Setup & Usage  
1. Clone the repository:  
   ```bash  
   git clone <repo-url>  
   cd <project-folder>  
   ```  

2. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  

3. **Select Database**:  
   - **SQLite**: Uses `student.db`.  
   - **MySQL**: Enter MySQL credentials in the sidebar.  

4. **Start Chatting**:  
   - Enter your **GROQ API key**.  
   - Ask database-related queries in **natural language**.  
   - View responses from the AI-powered SQL agent.  

## 🛠️ Technology Stack  
- **Frontend**: Streamlit  
- **AI Model**: Llama3-8b-8192 via ChatGroq  
- **Database Handling**: SQLite & MySQL (via SQLAlchemy)  
- **Backend Framework**: Langchain  
- **AI Agents**: Used for optimized query execution  

## 🎯 Future Enhancements  
- 🔹 **PostgreSQL support**  
- 🔹 Enhanced query optimization  
- 🔹 User authentication for security  

## 🤝 Contributing  
Contributions are welcome! Feel free to submit pull requests. 
