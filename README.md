# 🧠 taldetect-be

**taldetect-be** is the backend of the *taldetect* system, designed to analyze doctor-patient conversations and generate automated reports based on the **TALD** (Typical Atypical Language Dimension) scale.  
It leverages language models (LLMs), advanced audio processing, and NLP to support clinical evaluation through structured communication analysis.

👉 This backend powers the frontend available at this link:  
**[https://github.com/imlodo/taldetect-fe]**

---

## ✨ Key Features

- 🎙️ Automatic transcription of audio with **Whisper**
- 🧠 NLP and linguistic analysis with **spaCy** and **Transformers**
- 📈 Automatic extraction of **TALD scores**
- 📄 Generation of readable, printable multi-page PDF reports
- 🔍 Recognition of **linguistic patterns** like echolalia, verbigeration, repetitions, etc.
- 🔐 JWT authentication integrated with Firebase
- ☁️ Connection to MongoDB Atlas for data storage
- 📬 Report delivery via email
- 🌐 Quick API access even in cloud/Colab environments (via `ngrok`)

---

## 🛠 Tech Stack

| Category        | Key Libraries and Tools                          |
|-----------------|--------------------------------------------------|
| Web API         | FastAPI, CORS, OAuth2, JWT                       |
| Audio Analysis  | Whisper, torchaudio, pydub, parselmouth          |
| NLP & LLM       | spaCy, HuggingFace Transformers, text-generation |
| PDF Report      | ReportLab, FPDF                                  |
| Database        | MongoDB, motor, pymongo, Firebase                |
| Security        | bcrypt, JWT, Firebase Auth                       |
| Diarization     | pyannote.audio                                    |
| Others          | Google Colab, smtplib, ngrok, asyncio            |

---


MIT License.
© 2025 — taldetect project developed with ❤️ for research and mental health.
