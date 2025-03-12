# AI Conversational Data Science Tutor

This is an AI-powered **Conversational Data Science Tutor** built using **Streamlit**, **LangChain**, and **Google Gemini AI**. It provides expert assistance on **data science-related** questions, including Machine Learning, AI, Statistics, and Python.

---

## 🚀 Features
- **Conversational AI**: Engages users in an interactive Q&A session.
- **Memory Integration**: Remembers past interactions during a session.
- **Streamlit UI**: Clean and simple web interface.
- **Session Management**: Each user gets a unique session ID for chat history.
- **Google Gemini AI**: Uses `gemini-1.5-pro` for intelligent responses.
- **Environment Variables**: Secure API key handling using `.env`.

---

## 📦 Installation

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up API Key
Create a `.env` file in the root directory and add:
```sh
GOOGLE_API_KEY=your_google_api_key_here
```

---

## ▶️ Running the Application
Start the Streamlit app using:
```sh
streamlit run app.py
```

This will launch the AI tutor in your browser.

---

## 🛠️ Technologies Used
- **Python** 🐍
- **Streamlit** 🖥️
- **LangChain** 🧠
- **Google Gemini AI** 🤖
- **UUID for Session Management** 🔑

---

## 📝 Usage Instructions
1. Enter your **data science-related** question in the input field.
2. The AI Tutor responds with a clear explanation.
3. View the full chat history in the **Expandable Chat History** section.
4. Click **Clear Chat** to reset the conversation.

⚠️ **Note**: The AI will only answer **data science-related** questions. Any unrelated topics will be politely declined.

---

🔗 **Connect & Support**: If you find this useful, give it a ⭐ on GitHub!

