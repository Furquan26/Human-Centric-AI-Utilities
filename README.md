# Human-Centric AI Utilities

This repository features advanced Python tools designed to bridge the gap between machine logic and human communication.

## 🚀 Projects Included

### 1. AI Interview Simulation System
A voice-first interview practice tool that uses NLP to provide real-time feedback.
* **Voice Interaction:** Utilizes `speech_recognition` for input and `pyttsx3` for verbal output.
* **Sentiment Assessment:** Employs NLTK's VADER to analyze the confidence and tone of candidate responses.
* **Dynamic Scoring:** Automatically evaluates answers based on keyword matching, response length, and sentiment analysis.
* **Question Banks:** Includes curated technical and behavioral questions for Python and Machine Learning roles.

### 2. Colloquial Contextual Translator
A translation engine optimized for natural, human-sounding conversations.
* **Natural Refinement:** Features a custom regex-based mapping system to convert formal translations into colloquial Hindi.
* **Dual-API Fallback:** Implements a robust architecture that switches between Google Translator and MyMemory API to ensure constant availability.
* **Smart Dialect Handling:** Adjusts formal pronouns (e.g., 'Aap' to 'Tum') and verb conjugations to sound more conversational.

## 🛠️ Technical Stack
* **Language:** Python
* **NLP & Text:** NLTK, Regular Expressions (`re`)
* **APIs:** Deep Translator (Google & MyMemory)
* **Audio:** SpeechRecognition, Pyttsx3

## 📦 Installation
```bash
pip install nltk deep-translator SpeechRecognition pyttsx3
