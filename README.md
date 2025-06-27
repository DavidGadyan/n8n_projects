# 🏗️ n8n Projects

This repository contains automation projects built using [n8n](https://n8n.io), the powerful fair-code workflow automation tool.

---

<details>
<summary>🤖 Project: <code>chatbot_n8n</code></summary>

> 🚀 **Opening**: A smart, AI-powered chatbot designed for a real estate company to assist digital nomads in finding suitable homes and answer common queries. It uses OpenAI's GPT-4o for semantic search and Pinecone as a vector database.

### 🔧 Workflows Included

#### 📄 `gdrive2pinecone`

- Monitors Google Drive for newly created documents.
- Extracts text and generates embeddings using **OpenAI GPT-4o**.
- Uploads the embeddings to **Pinecone** for semantic search capabilities.

**Workflow Preview:**

![gdrive2pinecone Workflow](https://github.com/DavidGadyan/n8n_projects/blob/main/chatbot_n8n/gdrive2pinecone.png)

#### 💬 `chatbot_contact`

- Acts as the backend for the chatbot UI.
- Accepts questions from users about available homes.
- Uses Pinecone to find the most relevant documents and responds using GPT-4o.
- Collects customer contact details and saves them to **Google Sheets**.

**Workflow Preview:**

![n8n Chatbot Workflow](https://github.com/DavidGadyan/n8n_projects/blob/main/chatbot_n8n/n8n_chatbot.png)

### 🌐 Try It Live

👉 [Live Chatbot (n8n Cloud)](https://davidgadyan.app.n8n.cloud/webhook/854c829c-2ce6-426f-89e2-ed44d33182f3/chat)

### 🧠 Technologies Used

- **n8n** – Low-code workflow automation
- **OpenAI GPT-4o** – Embedding and response generation
- **Pinecone** – Vector similarity search
- **Google Drive & Google Sheets** – For document source and lead management

> ✅ **Closing**: This chatbot system shows how AI and automation can streamline customer interaction and lead generation for real estate.

</details>

---

<details>
<summary>🤖 Project: <code>ai_assistant</code></summary>

> 🚀 **Opening**: An advanced AI Assistant that helps manage daily productivity tasks like researching topics, handling calendar events, sending emails, and automating social media content creation.

### 💼 Capabilities

- Research any topic from the Web.
- Create, update, and delete calendar events.
- Send emails using Gmail.
- Save contact information to Google Sheets.
- Generate posts for X (formerly Twitter).

**Workflow Preview:**

![AI Assistant Workflow](https://github.com/DavidGadyan/n8n_projects/blob/main/ai_assistant/ai_assistant.png)

**Video Demo:**

![AI Assistant Demo](https://github.com/DavidGadyan/n8n_projects/blob/main/ai_assistant/ai_assistant_telegram.gif)

### 🧠 Technologies Used

- **n8n** – Low-code workflow automation
- **OpenAI GPT-4o** – Embedding and content generation
- **Google Calendar** – For scheduling and event management
- **Gmail** – For sending emails
- **Google Sheets** – For contact management
- **X (formerly Twitter)** – For post generation

> ✅ **Closing**: Perfect for entrepreneurs and busy professionals—this assistant showcases how n8n can bring AI productivity tools into your daily workflow.

</details>
