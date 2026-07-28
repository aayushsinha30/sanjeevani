# Sanjeevani — AI-Powered Multilingual Health Triage Web Application

This is the full-stack web application for **Sanjeevani** (संजीवनी), powered by **Gemma 4 / Gemini AI** for regional Indian dialect health triaging.

## 🚀 Quick Start Instructions

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Configure Environment Variables**:
   Create a `.env` file or export `GEMINI_API_KEY`:
   ```env
   GEMINI_API_KEY="your_google_ai_studio_api_key_here"
   ```

3. **Start Development Server**:
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser.

4. **Build for Production**:
   ```bash
   npm run build
   npm start
   ```

## 🛠 Tech Stack
- **Frontend**: React 19, TypeScript, Tailwind CSS, Lucide Icons, Motion
- **Backend**: Express.js, Vite Middleware
- **AI Engine**: Google GenAI SDK (@google/genai) with Gemma 4 / Gemini models