# Mental Health AI Chatbot

This project implements an AI-powered **mental health chatbot** designed to support individuals experiencing psychological distress.  
The chatbot focuses on understanding the user’s emotional state, offering empathetic responses, practical coping advice, and step-by-step guidance aimed at emotional regulation and self-support — **without providing medical diagnoses, medications, or any potentially harmful instructions**.

The system is built to act as a supportive conversational companion that helps users feel understood and guided in a safe and responsible manner.

---

## 🧠 Project Overview

The chatbot was developed and trained primarily using **Google Colab**, with experiments conducted on **A100 GPUs** to support large-scale language models.  
A conversational Large Language Model was fine-tuned and adapted to the mental health domain using curated dialogue datasets and prompt engineering techniques.

The model was designed to operate in a **chat-based conversational setting**, maintaining context across turns while enforcing safety and ethical constraints.  
The project also includes an interactive demo deployed as a **Hugging Face Space** using **Gradio**, allowing real-time user interaction with the chatbot.

---

## ✨ Key Features

- Domain-specific chatbot focused on **mental health support**  
- Emotion-aware and empathetic conversational responses  
- Step-by-step coping guidance and practical self-help suggestions  
- Safety-oriented prompt design (no medical advice or medication recommendations)  
- Conversational memory across dialogue turns  
- Fine-tuned and instruction-adapted LLM for chat-based interaction  
- Interactive web interface deployed via Hugging Face Spaces (Gradio)

---

## 🧠 Model & Training Details

- Base model: **Qwen (3B parameters)**  
- Training hardware: **NVIDIA A100 GPU**  
- Training approach:
  - Fine-tuning with **LoRA** for efficient adaptation  
  - Experiments conducted **with and without LoRA** for comparison  
- Optimizations:
  - **Flash Attention** for faster and more memory-efficient training  
- Training objective:
  - Improve empathetic response quality  
  - Enhance conversational coherence and safety in mental health contexts  

---

## 🛠️ Technologies

- **Python**
- **Transformers (Hugging Face)**
- **Large Language Models (LLMs)**
- **Qwen 3B**
- **LoRA (Low-Rank Adaptation)**
- **Flash Attention**
- **Prompt Engineering**
- **Gradio** (interactive UI)
- **Hugging Face Spaces**
- **Google Colab (A100 GPU)**

---

## 📂 Project Structure
MentalHealth-ChatBot/
│
├── Data/ # Curated mental health dialogue datasets
├── MentalHealth_ChatBot.ipynb
├── README.md

---

## ⚠️ Disclaimer

This chatbot is intended for **educational and research purposes only**.  
It does not replace professional mental health care, diagnosis, or treatment.
