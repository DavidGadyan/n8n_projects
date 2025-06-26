# 🏗️ n8n Projects

This repository contains automation projects built using [n8n](https://n8n.io), the powerful fair-code workflow automation tool.

---

## 🤖 Project: `chatbot_n8n`

A smart, AI-powered chatbot designed for a real estate company to assist digital nomads in finding suitable homes and answer common queries. It uses OpenAI's GPT-4o for semantic search and Pinecone as a vector database.

### 🔧 Workflows Included

---

#### 📄 `gdrive2pinecone`

This workflow:

- Monitors Google Drive for newly created documents.
- Extracts text and generates embeddings using **OpenAI GPT-4o**.
- Uploads the embeddings to **Pinecone** for semantic search capabilities.

**Workflow Preview:**

![gdrive2pinecone Workflow](https://github.com/yourusername/your-repo/blob/main/chatbot_n8n/gdrive2pinecone.png)

---

#### 💬 `chatbot_contact`

This workflow:

- Acts as the backend for the chatbot UI.
- Accepts questions from users about available homes.
- Uses Pinecone to find the most relevant documents and responds using GPT-4o.
- Collects customer contact details and saves them to **Google Sheets** for lead follow-up.

**Workflow Preview:**

![n8n Chatbot Workflow](https://github.com/yourusername/your-repo/blob/main/chatbot_n8n/n8n_chatbot.png)

---

### 🌐 Try It Live

You can test the chatbot live at the link below:

👉 [Live Chatbot (n8n Cloud)](https://davidgadyan.app.n8n.cloud/webhook/854c829c-2ce6-426f-89e2-ed44d33182f3/chat)

---

### 🧠 Technologies Used

- **n8n** – Low-code workflow automation
- **OpenAI GPT-4o** – Embedding and response generation
- **Pinecone** – Vector similarity search
- **Google Drive & Google Sheets** – For document source and lead management

---

### 📁 Folder Structure

