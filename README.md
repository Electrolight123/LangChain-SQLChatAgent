# 🦜 LangChain-SQLChatAgent

![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)
![License](https://img.shields.io/github/license/Electrolight123/LangChain-SQLChatAgent)
![Stars](https://img.shields.io/github/stars/Electrolight123/LangChain-SQLChatAgent?style=social)
![Issues](https://img.shields.io/github/issues/Electrolight123/LangChain-SQLChatAgent)
![Forks](https://img.shields.io/github/forks/Electrolight123/LangChain-SQLChatAgent?style=social)

> A powerful, interactive SQL chatbot built using [LangChain](https://www.langchain.com/), [Streamlit](https://streamlit.io/), and [Groq](https://groq.com/) LLaMA3 models. This tool enables users to communicate with relational databases (SQLite or MySQL) using natural language queries. Ideal for data analysts, developers, or educators who want a hands-free way to explore and interact with their databases.

---

## 🖼️ Social Preview Banner

<p align="center">
  <img src="assets/social-preview.png" alt="LangChain SQL Chat Agent - Social Banner"/>
</p>

---
## 🚀 Features

- 🔗 Connects to both **SQLite** and **MySQL** databases.
- 💬 Enables natural language querying using **Groq's LLaMA3-8B** model.
- 🧠 Uses **LangChain's SQL agent** and **toolkits** for dynamic SQL generation.
- 🖥️ Simple and elegant UI with **Streamlit**.
- 🔒 API key secured access and configurable MySQL credentials.

---

## 🧪 Demo Preview

<p align="center">
  <img src="assets/screenshot.png" alt="App Screenshot" />
</p>

---

## 🏗️ Project Structure

.
├── app.py # Main Streamlit application
├── sqlite.py # Script to create and populate a sample SQLite DB
├── student.db # SQLite database file (auto-generated)
├── requirements.txt # Python dependencies
└── README.md # This file

yaml
Copy
Edit

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electrolight123/LangChain-SQLChatAgent.git
cd LangChain-SQLChatAgent
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Generate Sample SQLite DB

```bash
python sqlite.py
```

### 4. Run the App

```bash
streamlit run app.py
```

---

## 🔐 API Key Setup
You'll need a Groq API key to use the LLaMA3 model. You can get one from [Groq Cloud]([https://console.groq.com/home]).

Paste it into the sidebar input field when prompted in the app.

---

## 📡 MySQL Configuration
If you want to use your own MySQL database:

Choose "Connect to your MySQL Database" in the sidebar.

Provide:

Host

Username

Password

Database name

Make sure your DB is accessible and contains some data for querying.

---

## 🧠 Example Queries
"List all students who scored more than 80."

"How many students are in Data Science class?"

"Show names of students in section A."

---

## 📌 Dependencies
langchain

langchain_groq

streamlit

sqlalchemy

mysql-connector-python

python-dotenv

validators

---

## 💡 Future Enhancements
✅ Add PostgreSQL support

✅ Add file upload for SQL dumps

✅ Improve response formatting

✅ Add export options for query results

---

## 📜 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
Abhishek Bala
B.Tech @ NIT Rourkela
Feel free to connect on LinkedIn or check out more at GitHub

## 🌟 Show Your Support
If you find this project useful, consider giving it a ⭐ and sharing it with your network!
