# 🎙️ Fine-Tuning SpeechT5 for Text-to-Speech using LJSpeech

This project fine-tunes [Microsoft's SpeechT5](https://huggingface.co/microsoft/speecht5_tts) model on the [LJSpeech](https://huggingface.co/datasets/keithito/lj_speech) dataset to synthesize custom, high-quality speech using Hugging Face Transformers and SpeechBrain.

## Check out the fine-tuned model here:  
👉 [farazashraf/speecht5_finetuned_enhanced](https://huggingface.co/farazashraf/speecht5_finetuned_enhanced)

---

## 📌 Overview

- 🔹 Preprocessed and normalized the [LJSpeech dataset](https://huggingface.co/datasets/keithito/lj_speech)
- 🔹 Generated speaker embeddings using `speechbrain/spkrec-xvect-voxceleb`
- 🔹 Used `SpeechT5Processor` for feature extraction and tokenization
- 🔹 Fine-tuned the model with `Trainer` from Hugging Face
- 🔹 Uploaded final model to Hugging Face Hub

---

## 🛠️ Installation

```bash
pip install transformers sentencepiece soundfile datasets speechbrain num2words librosa huggingsound
