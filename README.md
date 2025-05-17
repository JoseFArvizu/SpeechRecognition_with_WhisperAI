# 📢 Speech Recognition with OpenAI Whisper

This project demonstrates how to perform automatic speech recognition (ASR) using OpenAI's Whisper model. It includes transcription of audio files and evaluation using standard metrics like **WER** (Word Error Rate) and **CER** (Character Error Rate).

## 🔧 Features

- Transcribe audio files (`.wav`) using Whisper
- Compare transcriptions against ground truth
- Evaluate transcription performance using:
  - Word Error Rate (WER)
  - Character Error Rate (CER)

## 🧰 Technologies Used

- Python
- [OpenAI Whisper](https://github.com/openai/whisper)
- [jiwer](https://github.com/jitsi/jiwer) (for WER and CER calculations)
- Jupyter Notebook

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/SpeechRecognition_with_WhisperAI.git
cd SpeechRecognition_with_WhisperAI
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open `SpeechRecognition_with_WhisperAI.ipynb` using Jupyter and follow the instructions to test audio transcriptions.

## 📂 File Structure

```
SpeechRecognition_with_WhisperAI/
├── SpeechRecognition_with_WhisperAI.ipynb
├── speech_01.wav
├── README.md
└── requirements.txt
```

## 📈 Example Output

The notebook uses the Whisper model to transcribe `speech_01.wav` and compares the result with a ground truth transcription to calculate accuracy metrics.

## ✅ License

MIT License
