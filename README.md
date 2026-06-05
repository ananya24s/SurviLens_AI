# SurviLensAI

An AI-powered mobile assistant designed for real-world safety, navigation, and emergency support.  
SurviLensAI combines AI chat, voice interaction, offline maps, vision assistance, and emergency tools into a single mobile system built for critical and low-connectivity environments.

---

## Key Features

AI Assistant  
Natural language chat with context-aware responses for safety, survival, and navigation.

Voice Interaction  
Speech-to-text and text-to-speech support for hands-free usage in emergency situations.

Offline Maps  
Offline location support and navigation designed for low or no network scenarios.

Vision Assistance  
Camera-based AI assistance for understanding real-world surroundings.

Emergency System  
Quick-access SOS features and emergency response templates for fast action in critical situations.

Nearby Connectivity (Experimental)  
Peer-based nearby communication system designed for disaster or offline scenarios.

---

## Tech Stack

React Native (TypeScript)  
Android Native (Kotlin)  
iOS Native (Swift / Objective-C Bridge)  
AI Integration (Tool-calling / LLM APIs)  
Mapbox for maps and navigation  
Speech-to-Text and Text-to-Speech APIs  

---

## Project Structure

src/  
components/ – Reusable UI components  
screens/ – Application screens (Chat, SOS, Maps, Vision, etc.)  
services/ – AI, vision, and system logic  
navigation/ – App navigation structure  
hooks/ – Custom React hooks  
utils/ – Helper functions and emergency logic  
theme/ – Styling system and design tokens  

---

## Setup Instructions

Clone the repository  
git clone https://github.com/ananya24s/SurviLens_AI.git  
cd SurviLens_AI  

Install dependencies  
npm install  

iOS setup  
cd ios  
pod install  

Run the app  
npm run android  
or  
npm run ios  

---

## Environment Variables

Create a .env file in the root directory  

OPENAI_API_KEY=your_key_here  
MAPBOX_ACCESS_TOKEN=your_token_here  

---

## Project Highlights

Built for real-world emergency and survival scenarios  
Works in offline or low-connectivity environments  
Integrates AI, voice, vision, and maps in a single system  
Demonstrates production-level React Native architecture  
Includes native Android and iOS modules  

---

## Future Improvements

Offline AI inference support  
Satellite-based emergency fallback system  
Advanced mesh networking for disaster scenarios  
Wearable device integration  
Real-time emergency alert system  



