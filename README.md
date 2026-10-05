# 🎙️ Arabic Anime Characters Audio Transcription

A small Arabic Speech Recognition project using audio samples from **three different anime characters**.

The project experiments with two pretrained speech recognition models to transcribe the characters' Arabic speech into text.

## 🎯 Project Goal

The goal is to explore how different pretrained ASR models handle Arabic speech from different anime character voices.

```text
🎤 Anime Character Audio
        ↓
 ┌──────┴──────┐
 ↓             ↓
Whisper    Cohere Arabic ASR
 ↓             ↓
📝 Arabic Transcription
```

## 🎧 Audio Dataset

The project currently contains audio recordings from **three different anime characters**.

The recordings are used as input for the speech recognition models.

## 🤖 Models

### OpenAI Whisper

Whisper is used as the first speech recognition model to transcribe the Arabic audio.

### Cohere Arabic ASR

The project also uses:

`CohereLabs/cohere-transcribe-arabic-07-2026`

This model is used to generate Arabic transcriptions from the same audio.

## 🛠️ Technologies

- Python
- PyTorch
- OpenAI Whisper
- Hugging Face Transformers
- Cohere Arabic ASR
- Audio Processing

## ⚙️ Process

1. Load an audio recording from one of the three anime characters.
2. Process the audio for speech recognition.
3. Transcribe the audio using Whisper.
4. Transcribe the audio using the Cohere Arabic ASR model.
5. Compare the generated Arabic transcriptions.

## 📌 Current Status

- [x] Collect audio samples from three anime characters
- [x] Test Arabic speech recognition with Whisper
- [x] Test Arabic speech recognition with Cohere ASR
- [x] Generate Arabic transcriptions
- [ ] Compare model performance
- [ ] Build a character voice classification model
- [ ] Predict the character from an unseen audio recording
- [ ] Add a Gradio interface

## 👩‍💻 Author

**Lujain**

BCs Data Science interested in Python, Machine Learning, AI, NLP, and Speech Processing.
