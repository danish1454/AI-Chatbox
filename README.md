# AI Chatbox

**AI Chatbox** is a lightweight web-based chatbot built with HTML, CSS, and JavaScript, enhanced using the **Google Gemini API** for intelligent, AI-powered responses. This project is perfect for beginners looking to integrate AI into frontend applications.

![Chatbot Interface](bot.jpg)

---

## ✨ Features

- 🌐 Clean and responsive UI
- 🧠 AI-powered responses using Google Gemini
- ⚡ Fast and lightweight — no backend required
- 🛠️ Easy to customize and extend

---

## 🚀 Demo

To see the chatbot in action, simply open the `index.html` file in your browser after setting up your API key.

---

## 🧩 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **AI Integration**: [Google Gemini API](https://ai.google.dev)

---

## 📥 Getting Started

### ✅ Prerequisites

- A modern web browser (Chrome, Firefox, etc.)
- A valid **Google Gemini API key**

### 🔧 Installation Steps

1. **Clone the Repository**

```bash
git clone https://github.com/danish1454/AI-Chatbox.git
cd AI-Chatbox
```

2. **Get a Google Gemini API Key**

- Go to [Google AI Studio](https://makersuite.google.com/app)
- Sign in and create an API key from the "Get API key" section

3. **Configure Your API Key**

- Open `script.js`
- Replace the placeholder `'YOUR_API_KEY_HERE'` with your actual API key:

```javascript
const API_KEY = 'YOUR_API_KEY_HERE';
```

---

## 🧪 How to Use

1. Open the `index.html` file in your browser.
2. Enter your message in the chat input box.
3. Press **Send** or hit **Enter**.
4. The AI will respond based on your message using Google Gemini.

---

## 📁 Project Structure

```
AI-Chatbox/
├── index.html       # Main UI
├── styles.css       # Chatbot styling
├── script.js        # Gemini API integration + interaction logic
├── bot.jpg          # Bot profile image
└── user.jpg         # User profile image
```

---

## 🔐 Security Note

> Never expose your API key in a public repository.  
If you're deploying this project, use environment variables or a secure backend proxy to handle requests securely.

---

## 🧩 Customization

You can:
- Change styles in `styles.css`
- Modify chat logic in `script.js`
- Connect to other AI APIs or customize Gemini prompts

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

