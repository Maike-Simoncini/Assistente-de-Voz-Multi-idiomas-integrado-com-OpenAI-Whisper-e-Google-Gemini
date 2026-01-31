# 🎙️ Assistente de Voz Multi-idiomas

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maike-Simoncini/Assistente-de-Voz-Multi-idiomas-integrado-com-OpenAI-Whisper-e-Google-Gemini/blob/main/Assistente_de_Voz_Multi_idiomas_integrado_com_OpenAI_Whisper_e_Google_Gemini.ipynb)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![OpenAI Whisper](https://img.shields.io/badge/AI-Whisper-blueviolet)
![Google Gemini](https://img.shields.io/badge/AI-Gemini-orange)

Um assistente de voz inteligente capaz de ouvir, transcrever (usando OpenAI Whisper) e responder perguntas de forma contextual (usando Google Gemini Pro), com suporte a múltiplos idiomas.

---

## 🚀 Funcionalidades

* **Gravação de Áudio via Browser:** Interface em JavaScript integrada ao Python para capturar áudio diretamente do Google Colab.
* **Transcrição de Alta Precisão:** Utiliza o modelo **Whisper da OpenAI** para transformar fala em texto.
* **Inteligência Artificial Generativa:** Processamento de respostas através do **Google Gemini**, garantindo diálogos fluidos e inteligentes.
* **Multi-idiomas:** Suporte nativo para Português, Inglês e outros idiomas suportados pelos modelos.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Speech-to-Text:** [OpenAI Whisper](https://github.com/openai/whisper)
* **LLM (Large Language Model):** [Google Gemini AI](https://ai.google.dev/)
* **Interface de Gravação:** JavaScript + HTML5 MediaRecorder API

---

## 📋 Pré-requisitos

Para rodar este projeto, você precisará de uma chave de API do Google Gemini.
1.  Obtenha sua chave em: [Google AI Studio](https://aistudio.google.com/)
2.  No notebook, configure a variável de ambiente ou o input para a sua `API_KEY`.

---

## 🔧 Como Usar

1.  **Abrir no Colab:** Clique no botão "Open In Colab" no topo deste README.
2.  **Instalar Dependências:** Execute as primeiras células para instalar o `openai-whisper` e o SDK do `google-generativeai`.
3.  **Gravar Áudio:**
    * Execute a célula de gravação.
    * Fale sua pergunta ou comando.
    * O áudio será processado automaticamente.
4.  **Receber Resposta:** O assistente exibirá a transcrição e a resposta gerada pelo Gemini logo abaixo.
