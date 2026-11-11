# 🌍 Multilingual AI Voice Assistant

## 📌 Project Overview

The **Multilingual AI Voice Assistant** is an AI-powered application developed using Python and Streamlit. It allows users to interact with an AI assistant through voice and text input.

The application uses OpenAI Whisper for speech recognition, FLAN-T5 for AI response generation, language detection for identifying the user's language, Google Translator for translation, and gTTS for converting text responses into speech.

The main objective of this project is to make AI interaction easier and more accessible for users who prefer communicating in their own language.

## 🚀 Key Features

- 🎤 **Voice Input:** Record voice messages using a microphone.
- 📝 **Speech Recognition:** Convert spoken language into text using Whisper.
- 🌐 **Language Detection:** Automatically identify the user's language.
- 🔄 **Language Translation:** Translate user messages into English and translate AI responses back into the detected language.
- 🤖 **AI Response Generation:** Generate intelligent responses using the FLAN-T5 model.
- 🔊 **Text-to-Speech:** Convert AI-generated responses into audio using gTTS.
- 💬 **Text Chat:** Interact with the assistant using text input.
- 📜 **Conversation History:** Maintain conversation history during the application session.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| OpenAI Whisper | Speech-to-text conversion |
| Hugging Face Transformers | AI model integration |
| FLAN-T5 Base | AI response generation |
| Google Translator | Language translation |
| Langdetect | Language detection |
| gTTS | Text-to-speech conversion |
| PyTorch | Deep learning framework |
| Audio Recorder Streamlit | Voice recording |

## ⚙️ Application Workflow

1. User provides input through voice or text.
2. Whisper converts voice input into text.
3. Language detection identifies the input language.
4. The input is translated into English.
5. FLAN-T5 generates an AI response.
6. The generated response is translated into the user's detected language.
7. gTTS converts the response into speech.
8. The application displays the response and plays the generated audio.

## 📂 Project Structure

```text
Multilingual-AI-Voice-Assistant/
│
├── Multilingual_AI_voice_analyst.ipynb
│
└── README.md
```

## nstallation

Install the required Python libraries:

```bash
pip install streamlit
pip install transformers
pip install torch
pip install deep-translator
pip install langdetect
pip install gTTS
pip install audio-recorder-streamlit
pip install truststore
```

## How to Run

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project folder.

3. Save the final application code from the notebook as `app.py`.

4. Run the Streamlit application:

```bash
streamlit run app.py
```

5. Open the local URL displayed in the terminal.

6. Start interacting with the AI assistant using voice or text.

## Project Objective

The objective of this project is to develop a multilingual AI voice assistant that combines speech recognition, natural language processing, machine learning-based language generation, translation, and speech synthesis into a single application.

## Future Enhancements

- Add more language support.
- Integrate conversation memory for improved interactions.
- Implement advanced LLM models.
- Improve contextual understanding.
- Deploy the application on a cloud platform.

## Developer

**Nirmal Kumar**
