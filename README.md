# 🤖 ChatBot com IA (Streamlit + OpenAI)

Este projeto implementa um **chat interativo com Inteligência Artificial** utilizando **Streamlit** como frontend/backend e a API da **OpenAI** para geração de respostas.

---

## 🎯 Objetivo
- Criar uma interface simples e intuitiva de **chat em tempo real**.  
- Capturar as mensagens do usuário e enviá-las para o modelo de IA.  
- Exibir as respostas da IA diretamente na tela.  
- Armazenar o histórico de conversas durante a sessão.  

---

## 🛠️ Tecnologias utilizadas
- **Python**  
- **Streamlit** → criação do frontend e backend  
- **OpenAI API** → processamento de linguagem natural  

---

## 🚀 Funcionamento
1. O usuário escreve uma mensagem no campo de input.  
2. A mensagem é exibida no chat e enviada para a IA.  
3. A IA processa a entrada e retorna uma resposta.  
4. A resposta aparece na tela como mensagem do assistente.  
5. Todo o histórico da conversa é armazenado com `st.session_state`.  
