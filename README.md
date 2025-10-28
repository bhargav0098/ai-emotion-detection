# ai-emotion-detection
Here’s a **complete and professional README.md** for your **Voice-Driven Emotion Detection AI** project — with all required sections (setup, usage, structure, and contribution) written clearly and ready to upload to GitHub 👇

---

# 🎙️ Voice-Driven Emotion Detection AI

An AI-powered **voice emotion detection system** built with Python that listens to your voice, understands your emotional tone, and responds back intelligently using synthesized speech.

---

## 🚀 Features

* 🎧 **Voice Input** – Capture real-time speech from microphone using `SpeechRecognition` or `Whisper`.
* 🧠 **Emotion Detection** – Identify emotions like *happy, sad, angry, neutral, surprised*, etc., using a fine-tuned **BERT** model.
* 🗣️ **Voice Output** – Respond naturally with an AI-generated voice using `pyttsx3`, `gTTS`, or `edge-tts`.
* 🤖 **Smart Dialogue** – Generate empathetic and context-aware responses based on emotion.
* 💻 **Text Mode** – Option to run in text input/output mode.
* 🧩 **Modular Design** – Independent modules for capturing, transcribing, detecting emotion, and synthesizing voice.
* 🧪 **Batch Mode** – Process multiple audio files in bulk for offline analysis.

---

## 🛠️ Tech Stack

| Component              | Technology Used                  |
| ---------------------- | -------------------------------- |
| Programming Language   | Python                           |
| Speech Recognition     | `SpeechRecognition`, `Whisper`   |
| Emotion Classification | `transformers` (BERT)            |
| Text-to-Speech         | `pyttsx3`, `gTTS`, or `edge-tts` |
| Audio Handling         | `pyaudio`, `librosa`             |
| CLI Interface          | `argparse`                       |

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/voice-emotion-detection-ai.git
cd voice-emotion-detection-ai
```

### 2. Set Up Environment

```bash
python -m venv venv
source venv/bin/activate   # on macOS/Linux
venv\Scripts\activate      # on Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. (Optional) Run Setup Script

If included:

```bash
chmod +x setup.sh
./setup.sh
```

---

## ▶️ Usage

### 🎤 **Voice Mode**

Run the app to capture live voice and detect emotion:

```bash
python main.py --mode voice
```

### 💬 **Text Mode**

Provide text input directly:

```bash
python main.py --mode text
```

### 📁 **Batch Mode**

Process multiple audio files:

```bash
python main.py --batch ./audio_samples/
```

---

## 📂 Project Structure

```
voice-emotion-detection-ai/
│
├── data/                      # Sample audio or dataset files
├── models/                    # Pre-trained emotion detection model (BERT, etc.)
├── modules/
│   ├── audio_capture.py       # Handles microphone/audio input
│   ├── transcription.py       # Converts speech to text
│   ├── emotion_detection.py   # Predicts emotion from text
│   ├── voice_output.py        # Converts text back to speech
│   └── dialogue_engine.py     # Handles response logic
│
├── main.py                    # Entry point for CLI execution
├── requirements.txt           # Dependencies
├── setup.sh                   # Setup script (optional)
└── README.md                  # Documentation
```

---

## 🧠 Example Output

**Input (voice):**

> “I had such a terrible day.”

**Detected Emotion:** 😞 *Sad*
**Response (AI voice):**

> “I’m sorry to hear that. Want to talk about what happened?”

---

## 🧩 Future Enhancements

* 🎭 Add multimodal (voice + facial) emotion detection
* 🌐 Create web dashboard using Streamlit
* 🧬 Support emotion-based dialogue generation with GPT integration
* 💾 Store user emotion logs for pattern analysis

---

Demo
---
<img width="1301" height="380" alt="Screenshot 2025-10-28 235701" src="https://github.com/user-attachments/assets/3869eff0-9e88-49e2-9942-65118671cc03" />


## 📜 License

This project is licensed under the **MIT License**.
You’re free to use, modify, and distribute this software with attribution.

---

## 🧑‍💻 Author

**Renny (Bhargava Ram)**
📧 bhargavram085@.com

