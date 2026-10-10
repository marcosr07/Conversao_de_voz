# 🎙️ Assistente de Voz Multi-Idiomas com Whisper, ChatGPT e gTTS

Este repositório contém o código e a documentação de um projeto prático desenvolvido durante os labs da **DIO (Digital Innovation One)**. O objetivo é criar um sistema inteligente de conversação por voz multi-idiomas, integrando tecnologias de ponta em Inteligência Artificial para transcrição, processamento de linguagem natural e síntese de voz

---

## 🚀 Sobre o Projeto

O sistema é capaz de capturar áudio, transcrevê-lo com precisão (mesmo lidando com ruídos ou sotaques), processar a pergunta utilizando os modelos avançados da OpenAI e transformar a resposta gerada em áudio natural através do Google Text-to-SpeecH. 

A solução integra três grandes pilares tecnológicos:
1. **Speech-to-Text (Estímulo de Voz):** Utiliza o **Whisper** (da OpenAI), treinado com milhares de horas de dados multilíngues para reconhecimento automático de fala (ASR)
2. **Processamento de Linguagem Natural (LLM):** Utiliza a API do **ChatGPT (OpenAI)** para compreender a pergunta transcrita e formular uma resposta contextualizada e inteligente
3. **Text-to-Speech (Síntese de Voz):** Utiliza o **gTTS (Google Text-to-Speech)** para dar vida à resposta do ChatGPT em formato de áudio.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Python**
* **Google Colab** (Ambiente de desenvolvimento)
* **OpenAI Whisper** (`whisper`)
* **OpenAI API** (`openai` / ChatGPT)
* **Google Text-to-Speech** (`gTTS`)
* **JavaScript** (auxílio na captura de áudio no ambiente web/Colab)[cite: 1, 2]

---

## 📋 Passo a Passo da Implementação

O código está dividido nas seguintes etapas principais dentro do notebook:

1. **Gravação de Áudio:** Captura da fala do usuário utilizando Python e recursos auxiliares em JavaScript.
2. **Reconhecimento de Fala (Whisper):** Carregamento do modelo Whisper (`small`) para transcrever o arquivo de áudio gravado.
3. **Integração com a API do ChatGPT:** Envio da transcrição como prompt para o modelo de linguagem da OpenAI gerar uma resposta precisa.
4. **Sintetização de Voz (gTTS):** Conversão da resposta baseada em texto em um arquivo de áudio reproduzível (`.wav`)

---

## 💻 Como Executar

1. Acesse o notebook original do projeto no Google Colab através do link: [Google Colab - Assistente de Voz Multi-Idiomas](https://bit.ly/41XfKaM).
2. Configure a sua chave de API da OpenAI (`OPENAI_API_KEY`) no ambiente de execução
3. Execute as células sequencialmente para gravar sua voz, transcrever, processar via ChatGPT e ouvir a resposta gerada!

---

## 🔗 Links Úteis e Referências

* **Repositório do Código (Google Colab):** [Acessar Colab](https://bit.ly/41XfKaM)
* **Artigo Explicativo:** [Conversando Por Voz Com o ChatGPT Utilizando Whisper (OpenAI) e Python](https://bit.ly/41XfKaM) *(Material de apoio oficial da DIO)*
* **Live Explicativa no YouTube:** [Assistindo à Live Completa da DIO](https://bit.ly/44e9Nrw)

