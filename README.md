# Assistente_de_Voz_Inteligente_com_Gemini_-_Whisper
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](Chatbot.ipynb)

Este projeto é um assistente de voz funcional desenvolvido no Google Colab que integra tecnologias de ponta em Inteligência Artificial para processar áudio, entender o contexto e responder por voz.

## 🚀 Tecnologias Utilizadas
* **OpenAI Whisper:** Para transcrição robusta de áudio em texto.
* **Google Gemini 2.5 Flash:** O "cérebro" do assistente, responsável pelo processamento de linguagem natural.
* **gTTS (Google Text-to-Speech):** Para síntese de voz.
* **Pydub & FFmpeg:** Para pós-processamento de áudio (ajuste de velocidade).
* **JavaScript/HTML:** Interface interativa dentro do ambiente Python.

## 🛠️ Como Funciona
1. O usuário clica no botão interativo e fala por 5 segundos.
2. O Whisper transcreve o áudio para português.
3. O texto é enviado ao Gemini, que gera uma resposta inteligente.
4. A resposta é convertida em áudio, limpa de símbolos de formatação e acelerada para uma fala natural.

## 📋 Pré-requisitos
Para rodar este notebook, você precisará configurar uma `GEMINI_API_KEY` nos Secrets do seu Google Colab.
