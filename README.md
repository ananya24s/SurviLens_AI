# 🛡️ SurviLensAI

An AI-powered mobile assistant built for real-world safety, navigation, and survival support.  
SurviLensAI combines **computer vision, voice interaction, offline maps, and AI assistance** into a unified emergency-ready mobile experience.

---

## ✨ Key Features

### 🤖 AI Assistant
- Natural language chat with AI support
- Context-aware responses for survival, safety, and navigation
- Tool-calling based intelligent responses

### 🎙️ Voice & Speech Pipeline
- Speech-to-text for hands-free interaction
- Text-to-speech for real-time AI responses
- Voice-driven emergency interaction system

### 📍 Offline Maps & Location Awareness
- Offline map support for low-connectivity environments
- Nearby location detection
- Emergency route guidance

### 📷 Vision Assistance
- Camera-based assistant for real-world object understanding
- AI-powered visual guidance

### 🚨 Emergency System
- SOS quick-access interface
- Emergency templates and fast response actions
- Designed for critical low-time scenarios

### 🌐 Mesh / Nearby Connectivity (Experimental)
- Nearby peer-based communication system
- Designed for disaster/offline scenarios

---

## 🧠 Tech Stack

- **React Native (TypeScript)**
- **Android + iOS native modules**
- **OpenAI / AI Tool-calling system**
- **Mapbox (Offline maps integration)**
- **Speech-to-Text / Text-to-Speech APIs**
- **Native Android (Kotlin) + iOS (Swift/Obj-C bridge)**

---

## 📁 Project Structure


src/
├── components/ # UI components
├── screens/ # App screens (Chat, SOS, Maps, Vision)
├── services/ # AI, vision, mesh, model services
├── navigation/ # App navigation system
├── hooks/ # Custom React hooks
├── utils/ # Helpers (geo, emergency logic)
├── theme/ # Colors & styling system


---

## ⚙️ Setup Instructions

### 1. Clone repo
```bash
git clone https://github.com/ananya24s/SurviLens_AI.git
cd SurviLens_AI
2. Install dependencies
npm install
3. iOS setup
cd ios
pod install
4. Run app
npm run android
# or
npm run ios
🔐 Environment Variables

Create a .env file:

OPENAI_API_KEY=your_key_here
MAPBOX_ACCESS_TOKEN=your_token_here
🚀 Highlights (Why this project matters)
Built for real-world emergency scenarios
Works in offline / low connectivity environments
Combines AI + mobile systems + native modules
Demonstrates production-level architecture in React Native
Integrates multi-modal AI (voice, vision, text)
🧩 Future Improvements
Full offline AI inference support
Satellite-based emergency fallback
Improved mesh networking system
Wearable device integration
Real-time disaster alert system
