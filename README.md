# Inbaraj - AI Campus Assistant

Official AI Chatbot frontend for **Dr. MGR Educational and Research Institute (Chennai)**. Built with React + Vite and vanilla CSS.

## 🚀 Features

- **Full-page Chatbot UI:** Desktop centered card & full-screen mobile responsive layout.
- **Start Conversation Flow:** Prominent greeting screen on first load with session initialization.
- **Shift + Enter Support:** Supports multi-line message composing (`Shift + Enter` for new lines, `Enter` to send).
- **Multi-page Brochure Gallery:** Swipeable image carousel with left/right navigation, pagination dots, page counter, and image lightbox.
- **Session Persistence & History:** Saves current conversation in `sessionStorage` and maintains past conversations in a Chat History drawer.
- **Custom Collegiate Avatar:** Integrated high-resolution student graduate avatar.
- **Zero External UI Libraries:** Pure React (JSX) and plain CSS.

## 📦 Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd inbaraj-chatbot
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start local development server:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

## ⚙️ Configuration

The webhook URL is configured in `src/config.js`:

```javascript
export const WEBHOOK_URL = "https://athish-07.app.n8n.cloud/webhook/college-chat";
```

## 📁 Project Structure

```text
├── index.html
├── package.json
├── vite.config.js
├── .gitignore
├── README.md
├── public/
│   └── avatar.png
└── src/
    ├── assets/
    │   └── avatar.png
    ├── components/
    │   └── Chatbot.jsx
    ├── App.css
    ├── App.jsx
    ├── config.js
    └── main.jsx
```
