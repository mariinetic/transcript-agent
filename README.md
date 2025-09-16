# 🎬 Video Subtitle & Summary Generator

Este projeto facilita a criação de **legendas automáticas** e **resumos de vídeos** em português.  
Ideal para quem precisa legendar vídeos rapidamente, gerar transcrições e até ter um resumo do conteúdo.

---

## ✨ Funcionalidades
- 🎧 Extrai o áudio do vídeo (`.mp4` → `.mp3`)
- 📝 Transcreve o áudio para texto usando [OpenAI Whisper](https://github.com/openai/whisper)
- 📄 Gera legendas no formato `.srt`
- 🎞️ Insere legendas direto no vídeo usando **FFmpeg**
- 📑 Salva a transcrição completa em `.txt`
- 🧠 Gera **resumo automático** do conteúdo usando **LangChain + OpenAI**

---

## 📦 Instalação

No Google Colab, basta instalar os pacotes:

```bash
!pip install git+https://github.com/openai/whisper.git
!pip install moviepy pysrt langchain openai
