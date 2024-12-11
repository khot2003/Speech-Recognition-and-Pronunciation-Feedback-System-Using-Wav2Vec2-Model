# Speech-Recognition-and-Pronunciation-Feedback-System-Using-Wav2Vec2-Model


---

### **Introduction**

Students learning English as a second language (ESL) often struggle with pronunciation. Existing tools provide generic feedback, which may not address individual speech patterns or regional accents. This project aims to develop a speech-to-text system that analyzes spoken input, transcribes it into text, and provides targeted feedback for pronunciation improvement.

---

### **Motivation**

Learning proper pronunciation is critical for ESL students to enhance communication skills. However, traditional methods lack personalization and fail to cater to individual linguistic challenges. This system bridges that gap by providing phoneme-level analysis and actionable feedback, helping students improve their spoken English effectively.

---

### **Problem Statement**

Students learning English as a second language often face challenges in accurately pronouncing words due to differences in phonetic patterns and accents. Existing tools provide generic feedback without catering to individual speech patterns, making it hard for learners to address specific issues.

---

### **Objectives**

1. **Develop a speech-to-text system** that transcribes student audio into text.
2. **Fine-tune the Wav2Vec2 model** to better handle pronunciation nuances in ESL students' speech.
3. **Provide phoneme-level feedback** by comparing spoken input with correct pronunciation.
4. **Quantify performance** using Word Error Rate (WER) and Character Error Rate (CER) to validate system accuracy.

---



### **Technologies Used**

- **Wav2Vec2**: A pre-trained speech-to-text model by **Facebook AI** used for automatic speech recognition (ASR).
- **Phonemizer**: Converts text into phonetic representation for comparing spoken and reference pronunciations.
- **gTTS**: Google Text-to-Speech is used to generate audio feedback for correct pronunciations.
- **Torch**: For model inference and processing of audio.
- **Torchaudio**: For loading and processing audio data.


---

### RESULTS:

3. **Input**: Upload the student's audio file and enter the reference text (the correct pronunciation).
4. **Output**: The app will display the transcribed text, provide pronunciation feedback, and generate an audio file of the correct pronunciation.




---

### **Example Use Case**

1. **Audio Input**: A student submits an audio file saying "Can you give me the receipt?"
2. **Transcription**: The system transcribes the speech into text: "Can you give me the receipt?"
3. **Phoneme-level Feedback**: The system compares phonemes and identifies any discrepancies.
4. **Feedback**: The system flags incorrect phonemes, provides a correct pronunciation, and generates an audio file with the correct pronunciation.

---


