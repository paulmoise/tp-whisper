# 🗣️ Whisper-based Speech Transcription and Speaker Segmentation

This project explores **automatic speech transcription** using OpenAI's **Whisper** model and **speaker segmentation** using `pyannote.audio`. The main objective is to evaluate the transcription quality and analyze the impact of different Whisper model sizes on performance metrics like **WER (Word Error Rate)**.

---

## 📌 Objectives

1. **Transcribe Speech Audio**:  
   Use Whisper to transcribe a provided audio file and observe initial transcription results.

2. **Speaker Diarization & Evaluation**:  
   Segment the audio by speaker using `pyannote.audio`, and compute WER by comparing Whisper's output to the ground-truth transcript.

3. **Model Comparison**:  
   Evaluate the performance of different Whisper models (`small`, `medium`, `large`) on WER per speaker. Analyze whether larger models yield better transcription quality overall or for specific speakers.

---

## 🧠 Technologies Used

- [Whisper](https://github.com/openai/whisper) by OpenAI — for speech-to-text transcription.
- [pyannote-audio](https://github.com/pyannote/pyannote-audio) — for speaker diarization.
- `jiwer` — for WER calculation and comparison.
- Python, NumPy, Pandas, Matplotlib — for data manipulation and analysis.

---

## 🧪 Experiments

The experiments include:
- Running Whisper models on a single audio file.
- Applying speaker segmentation using `pyannote.audio`.
- Computing WER globally and per speaker.
- Comparing model sizes (small/medium/large) in terms of accuracy and efficiency.

---

## 📊 Results

You will find:
- Transcriptions for each model.
- Speaker-specific WER evaluations.
- Analysis on how model size influences performance.

---

## 🚀 How to Run

Check the notebook.

Use collab to benefit from the GPU.
