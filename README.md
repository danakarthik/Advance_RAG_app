# 🧠 AI Chatbot Backend (Spring AI + RAG)

 

---

## 🚀 Features

* AI chatbot using OpenAI (GPT models)
* Retrieval-Augmented Generation (RAG)
* Vector database integration (semantic search)
* Query transformation (rewrite + translation)
* Context-aware responses
* REST API for chat interaction
* Modular Spring Boot architecture

---

## 🏗️ Tech Stack

* Java
* Spring Boot
* Spring AI
* OpenAI API
* MariaDB (Vector Store)
* Maven

---

## 🧠 How It Works

User Query → Query Transformation → Vector Search → Context Retrieval → LLM → Response

---

## 📂 Project Structure

```bash
src/main/java/com/spring/ai/firstproject/
├── Config/
├── Controller/
├── Service/
├── helper/
```

---

## ⚙️ Key Implementation

### 🔹 Chat API

* Exposes REST endpoint to interact with chatbot

👉 Code: 

---

### 🔹 RAG Pipeline

* Query rewriting + translation
* Multi-query expansion
* Vector similarity search
* Context augmentation

👉 Code: 

---

### 🔹 Data Ingestion

* Stores custom knowledge into vector database

👉 Code: 

---

### 🔹 AI Configuration

* Configures OpenAI model + safety filters

👉 Code: 

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Add your OpenAI API Key in `application.properties`

👉 Config: 

3. Run the project

```bash
mvn spring-boot:run
```

---

## 🧪 API Usage

### Endpoint:

```
POST /chat?q=your-query
```

### Example:

```
/chat?q=What is Java?
```

---

## 🚀 Future Improvements

* Add frontend (React / Next.js)
* Add authentication (JWT)
* Deploy on AWS
* Multi-user chat sessions
* Build AI agents

---

## 👨‍💻 Author

Karthik Bharathapu
Java Full Stack Developer | Aspiring AI Engineer

---

## ⚠️ Important

Remove API keys before pushing to GitHub.
Use environment variables instead.

---
