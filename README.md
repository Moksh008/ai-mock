
# 🧠 AI Mock Interview App

An AI-powered mock interview web application designed to simulate real-time interview experiences. Built with React, Vite, and TypeScript, and styled using Tailwind CSS.

## 🌐 Live Demo

👉 [ai-mock-interview-henna.vercel.app](https://ai-mock-interview-henna.vercel.app)

---

## 🚀 Features

- 🎤 AI-generated mock interview questions (OpenAI/Gemini-compatible)
- 💬 Real-time speech-to-text using browser's Web Speech API
- 🔐 User authentication with Clerk
- 🔥 Firebase integration for data storage or user data
- 💻 Fully responsive UI built with Tailwind CSS
- ⚡ Blazing fast development using Vite

---

## 🛠 Tech Stack

| Technology                     | Purpose                                        |
|--------------------------------|------------------------------------------------|
| **React**                      | UI library                                     |
| **TypeScript**                 | Type-safe development                          |
| **Vite**                       | Frontend tooling                               |
| **Tailwind CSS**              | Utility-first CSS styling                     |
| **Clerk**                      | User authentication and account management     |
| **Firebase**                   | Realtime DB, Firestore, hosting (if used)      |
| **react-speech-recognition**   | Speech-to-text using Web Speech API            |
| **Vercel**                     | Deployment and hosting                         |

---

## 📁 Folder Structure

```

ai-mock/
├── public/               # Static files
├── src/
│   ├── components/       # Reusable components
│   ├── pages/            # Screens like Home, Interview, Result
│   ├── hooks/            # Custom hooks (e.g. speech-to-text)
│   ├── assets/           # Images, icons, etc.
│   ├── App.tsx           # Main app component
│   ├── main.tsx          # Entry point
│   └── config/           # Firebase or Clerk config
├── index.html
├── package.json
└── vite.config.ts

````

---

## ⚙️ Getting Started

1. **Clone the Repository**

```bash
git clone https://github.com/Moksh008/ai-mock.git
cd ai-mock
````

2. **Install Dependencies**

```bash
npm install
```

3. **Set Up Environment Variables**

Create a `.env` file and configure the following (example keys):

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_FIREBASE_API_KEY=your_firebase_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
```

4. **Run Development Server**

```bash
npm run dev
```

5. **Build for Production**

```bash
npm run build
```

6. **Preview Production Build**

```bash
npm run preview
```

---

## 🔐 Authentication

We use **Clerk** for secure and modern auth. Users can:

* Sign up / Sign in with email or OAuth
* Manage their profile
* Stay authenticated across sessions

---

## 🗣 Speech-to-Text

Powered by [`react-speech-recognition`](https://www.npmjs.com/package/react-speech-recognition), which uses the browser's Web Speech API:

* Press mic button to speak your answer
* Transcription appears in real-time
* Works best in supported browsers (Chrome, Edge)

---

## ☁️ Backend (Firebase)

Firebase is used for:

* Realtime database or Firestore (for storing sessions/interviews)
* Hosting (optional)
* Analytics or functions (optional)

---

## 📦 Deployment

Deployed via [Vercel](https://vercel.com/):

* Auto-deploys from `main` branch
* Supports preview deployments

---

## 🙌 Contributing

Contributions welcome! Please open an issue or PR.

---

## 📄 License

[MIT License]=

---

> Built with ❤️ by [Moksh Kulshrestha](https://github.com/Moksh008)


