# Interview Copilot Mobile 🚀

A stealthy, high-speed, real-time interview assistant built for mobile browsers. This tool listens to your interview questions and provides structured, senior-level technical answers using the Groq Llama 3.3 API.

## ✨ Key Features
- **Zero-Latency AI:** Powered by Groq for responses in under 1.5 seconds.
- **Hands-Free Operation:** Manual "Start/Stop" voice-to-text capture using the Web Speech API.
- **Stealth UI:** Toggle between "Stealth Mode" (looks like a documentation log) and "Pro Mode" (dark theme).
- **Context-Aware:** Upload your resume to get answers tailored to your specific project history.
- **Follow-up Memory:** Remembers the last few turns of the conversation for seamless follow-up questions.
- **Export to Word:** Save your entire interview transcript as a structured `.doc` file.
- **Privacy First:** Your API keys and resume data are stored exclusively in your browser's `localStorage`.

## 🛠️ Getting Started

### 1. Prerequisites
- A **Groq API Key** (Get one for free at [console.groq.com](https://console.groq.com/)).
- A mobile browser (Chrome or Safari) with Microphone permissions enabled.

### 2. Hosting on GitHub Pages
This app is a single-file `index.html`. To host it:
1. Create a new GitHub repository.
2. Upload `index.html` to the root.
3. Go to **Settings > Pages**.
4. Set the source to the `main` branch and click **Save**.
5. Open the provided URL on your phone.

## 🚀 Usage Tips
- **Placement:** Prop your phone horizontally under your monitor so it stays in your eye-line.
- **The "Senior" Tone:** The AI is tuned to provide first-person answers ("I usually find that...") to help you speak naturally.
- **Manual Control:** Tap **Start Question** when the interviewer begins speaking and **Stop & Answer** as soon as they finish to trigger the response.

## 🔒 Security Note
This application communicates directly with the Groq API. Your API Key is never sent to any intermediate server; it stays on your device.

## ⚖️ License
MIT License - Feel free to modify and use for your personal interview preparation.
