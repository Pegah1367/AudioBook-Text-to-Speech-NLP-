# Audiobook Generator from PDF Using Text-to-Speech

## Project Overview
This project implements an **end-to-end audiobook generation pipeline** that converts the contents of a PDF document into spoken audio.  
It demonstrates practical skills in **PDF text extraction, text preprocessing, text-to-speech (TTS) conversion, and audio file generation** using Python.

The final output is an **MP3 audiobook file** that can be played directly or distributed as an audio resource.

---

## Objectives
- Extract readable text from a PDF document
- Clean and prepare text for speech synthesis
- Convert text into natural-sounding speech
- Save the generated speech as an audio file
- Play the audio within the notebook environment

---

## System Workflow
1. Load a PDF file
2. Extract text from all pages
3. Preprocess and clean extracted text
4. Convert text to speech using a TTS engine
5. Save output as an audio file (`.mp3`)
6. Play the generated audiobook

---

## Text Extraction
- Library used: **PyPDF2**
- Reads PDF files page by page
- Extracts raw textual content into a single string
- Handles multi-page documents

This step transforms static document content into machine-readable text.

---

## Text-to-Speech Conversion
- Library used: **gTTS (Google Text-to-Speech)**
- Language: English
- Converts extracted text into spoken audio
- Outputs high-quality MP3 audio

The project demonstrates how textual content can be transformed into an accessible audio format using cloud-based TTS technology.

---

## Audio Output
- Audio saved as: `audiobook.mp3`
- Playable directly within Jupyter Notebook
- Compatible with standard media players

---

## Technologies Used
- Python
- PyPDF2 (PDF text extraction)
- gTTS (Text-to-Speech)
- IPython Audio display

---

## Skills Demonstrated
- Document processing and text extraction
- Natural Language Processing (NLP) fundamentals
- Text-to-Speech systems
- Audio file generation and handling
- End-to-end automation pipeline design

---

## Use Cases
- Audiobook creation
- Accessibility support for visually impaired users
- Converting study material into audio
- Content repurposing for podcasts or learning tools

---

## Limitations
- PDF text quality depends on document structure
- Scanned PDFs without embedded text require OCR
- gTTS requires an internet connection

---

## Future Enhancements
- Add OCR support for scanned PDFs
- Split audio into chapters or sections
- Support multiple languages and voices
- Integrate offline TTS engines (e.g., pyttsx3)
- Build a simple UI or web interface

---

## Conclusion
This project demonstrates a practical application of **NLP and speech technologies** by transforming static documents into audio content.  
It highlights the ability to integrate multiple libraries into a functional, user-oriented solution with real-world relevance.
