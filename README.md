# 📧 SmartMail AI – Intelligent Email Reply Assistant

SmartMail AI is an AI-powered email assistant that helps users generate smart, context-aware replies to emails based on desired tone and content. Built using **Spring Boot**, **Spring AI**, **React**, and the **Google Gemini API**, the project offers both a modern **web application** and a **Chrome extension**, enabling users to generate replies directly inside Gmail or through a custom UI.

---

## 🚀 Features

- 🤖 **AI-based Email Response Generator** using Google Gemini API and Spring AI
- 🎨 **Tone Customization**: Choose between Casual, Formal, or Professional tone
- 🔐 **Secure Backend** using Spring Boot and RESTful APIs
- 💻 **User-Friendly React Frontend** with clean UI/UX and real-time response
- 🌐 **Chrome Extension Integration** for replying to emails within Gmail
- ⚙️ Modular architecture with separation of frontend, backend, and extension

---

## 🛠️ Tech Stack

| Layer        | Technology                              |
|--------------|------------------------------------------|
| Backend      | Spring Boot, Spring AI, Google Gemini API |
| Frontend     | React, Tailwind CSS                      |
| Extension    | JavaScript, Chrome Extension APIs        |
| Languages    | Java, JavaScript, TypeScript, HTML, CSS  |
| Versioning   | Git, GitHub                              |

---

## 📂 Project Structure

smartmail-ai-assistant/
├── backend/ # Spring Boot backend with Spring AI and Gemini API
│ └── src/
├── frontend/ # React app with Tailwind CSS
│ └── src/
├── extension/ # Chrome extension for Gmail integration
│ └── scripts/
└── README.md

## 🧪 How It Works

1. User pastes an email or selects it from Gmail.
2. User selects a tone: `Casual`, `Formal`, or `Professional`.
3. Frontend sends the request to the Spring Boot backend.
4. Backend formats the prompt and sends it to **Google Gemini API** via **Spring AI**.
5. Gemini returns a response, which is sent back and displayed in the UI or injected in Gmail.

---

## 📦 Setup Instructions

### 🔧 Prerequisites

- Node.js (v18+)
- Java 17+
- Maven
- Google Gemini API Key
- Chrome browser (for extension)

---

### 🧱 Backend Setup (Spring Boot)

cd backend
# Add your Gemini API Key to application.properties
./mvnw spring-boot:run 

### Frontend Setup (React)
bash
Copy
Edit
cd frontend
npm install
npm start

## Acknowledgements
Google Gemini API
Spring AI
React
Tailwind CSS
