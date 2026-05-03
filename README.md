# 🤖 AI Personal Assistant

An AI-powered personal assistant built using **Flask**, **Groq API**, and a simple **HTML/CSS frontend**. This project allows users to interact with an intelligent chatbot through a clean web interface.

---

## 🚀 Features

* 🧠 AI chatbot powered by Groq API
* ⚡ Fast and responsive answers
* 🌐 Simple web interface using HTML & CSS
* 🔌 Flask backend for handling requests
* 💬 Interactive chat experience

---

## 🛠️ Tech Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS
* **AI API:** Groq

---

## 📂 Project Structure

```
AI-Personal-Assistant/
│
├── app.py
├── templates/
│   └── index.html
├── static/
│   ├── style.css
│   └── script.js
├── .env
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Vaishnavi-Chimkar/AI-Personal-Assistant.git
cd AI-Personal-Assistant
```

---

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

---

### 3. Install Required Packages

Since there's no `requirements.txt`, install manually:

```bash
pip install flask python-dotenv groq
```

---

### 4. Add Groq API Key

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

⚠️ Do not upload this file to GitHub.

---

## ▶️ Run the Application

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

## 🧩 How It Works

1. User enters a query
2. Flask backend processes it
3. Sends request to Groq API
4. AI response is returned
5. Displayed on the UI

---

## 💡 Use Cases

* Personal assistant
* AI chatbot project
* Learning Flask + APIs

---

## 🔒 Security

* Keep API keys private
* Use `.env` for sensitive data

---

## 📈 Future Improvements

* Voice assistant 🎤
* Chat history 📜
* Better UI 🎨
* Deployment ☁️

---

## 👩‍💻 Author

**Vaishnavi Chimkar**
GitHub: https://github.com/Vaishnavi-Chimkar

---

⭐ Star this repo if you like it!
