# 🤖 Groq AI Chatbot

A simple and interactive AI chatbot built with **Streamlit** and powered by **Groq's Llama models**. Users can chat with the AI in real time, choose different models, adjust generation settings, and maintain conversation history.

---

## 🚀 Features

- 💬 Interactive chat interface
- ⚡ Powered by Groq Llama models
- 🎛️ Model selection from sidebar
- 🌡️ Adjustable temperature
- 📝 Customizable maximum response tokens
- 🗑️ Clear chat history
- 💾 Session-based conversation memory
- 🎨 Clean and responsive Streamlit UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Groq API
- python-dotenv
- Llama 3 Models

---

## 📂 Project Structure

```
Groq-AI-Chatbot/
│
├── app.py              # Main Streamlit application
├── .env                # API Key (Not uploaded to GitHub)
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Groq-AI-Chatbot.git

cd Groq-AI-Chatbot
```

### 2️⃣ Create Virtual Environment (Optional)

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup Environment Variables

Create a `.env` file inside the project folder.

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from:

https://console.groq.com/keys

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The app will open automatically in your browser.

---

## 🖥️ User Interface

### Sidebar

- Select AI Model
- Adjust Temperature
- Set Maximum Tokens
- Clear Chat History

### Main Chat Window

- Type your prompt
- Receive AI-generated responses
- Conversation history is maintained during the session

---

## 🧠 Available Models

- Llama 3.3 70B Versatile
- Llama 3.1 8B Instant

---

## 📦 Requirements

```
streamlit
groq
python-dotenv
```

or install using

```bash
pip install -r requirements.txt
```

---

## 🔒 Security

Never upload your `.env` file or API keys to GitHub.

Add the following to `.gitignore`

```
.env
__pycache__/
*.pyc
```

---

## 📸 Demo

Add screenshots here.

Example:

```
images/
    chatbot.png
```

Then,

```markdown
![App Screenshot](images/chatbot.png)
```

---

## 🌟 Future Improvements

- Conversation export
- Multiple chat sessions
- Markdown rendering
- File upload support
- Streaming AI responses
- Dark/Light theme switch
- Chat history persistence
- Voice input
- Image understanding

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Create a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Pravallika Bonu**

- GitHub: https://github.com/Pravallika-1902
- LinkedIn: https://www.linkedin.com/in/pravallika-bonu/

---

⭐ If you found this project useful, don't forget to star the repository!
