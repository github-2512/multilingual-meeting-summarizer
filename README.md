# 🎙️ Multilingual Meeting AI: Transcription & Abstractive Synthesis

This repository contains the official implementation of a high-performance pipeline designed for the automated documentation of multilingual and code-switched meeting discourse.

## 📌 Abstract
As discussed in the associated research, this framework addresses the challenges of regional language processing (Kannada, Hindi, Punjabi) through a multi-stage NLP approach. It leverages OpenAI's Whisper for robust speech-to-text and Llama 3.3-70B via Groq LPU acceleration for generative correction and structured summarization.



## 🚀 Core Methodology
The system follows a four-stage pipeline as detailed in the methodology section:
1.  **Audio Acquisition:** Multi-source extraction (YouTube, Drive, or Local Files).
2.  **Speech-to-Text (STT):** Multilingual transcription with auto-detection.
3.  **Generative Correction:** LLM-based refinement to fix phonetic errors and remove disfluencies.
4.  **Abstractive Synthesis:** Generation of comprehensive, structured meeting reports.

## 🛠️ Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/github-2512/multilingual-meeting-summarizer.git](https://github.com/github-2512/multilingual-meeting-summarizer.git)
   cd multilingual-meeting-summarizer
