# 🤖 Nati | AI Coder  

Bem-vindo(a) ao **Nati | AI Coder**, um assistente virtual de **programação Python**, criado com **Streamlit** e alimentado pela **API do Groq**.  

O objetivo deste projeto é oferecer uma ferramenta prática e educativa para quem está aprendendo a programar, fornecendo explicações detalhadas, exemplos de código e referências oficiais da documentação Python.

---

## 🧠 O que é o Nati | AI Coder?

O **Nati | AI Coder** é um assistente especializado em **Python**, capaz de:
- Responder dúvidas de programação;
- Explicar conceitos e estruturas de dados;
- Gerar exemplos de código comentados;
- Indicar links oficiais da documentação.

Ele utiliza a **Groq API** para acessar modelos de linguagem avançados (como `openai/gpt-oss-20b`) e gerar respostas inteligentes e contextualizadas.

---

## 🚀 Funcionalidades

✅ Interface web interativa com **Streamlit**  
✅ Comunicação em tempo real com o modelo LLM via **Groq SDK**  
✅ Histórico de conversa armazenado com **st.session_state**  
✅ Inserção segura da **API Key** do usuário na barra lateral  
✅ Respostas formatadas com código, explicações e referências

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.13**
- **Streamlit**
- **Groq SDK**
- **python-dotenv** *(opcional para gerenciar chaves localmente)*
- **HTML + Markdown (para formatação no app)**

---

## 📦 Instalação e Execução

### 1️⃣ Clone este repositório
```bash
git clone https://github.com/nataliaguarnieri/portfolio-ia-projects/proj_1_AI_Coder.git
cd proj_1_AI_Coder
```

### 2️⃣ Crie e ative um ambiente virtual
```bash
python -m venv venv
```
* **Windows:**
```bash
venv\Scripts\activate
```
* **Mac/Linux:**
```bash
source venv/bin/activate
```

### 3️⃣ Instale as dependências
```bash
pip install -r requirements.txt
```

---

## 🔑 Configurando sua API Key da Groq

Para utilizar a IA, você precisa gerar sua própria chave de API gratuita no site da **Groq**:

👉 [https://console.groq.com/keys](https://console.groq.com/keys)

1. Crie uma conta gratuita;  
2. Gere uma nova **API Key**;  
3. Copie a chave e insira no campo lateral do app (“Insira sua API Key Groq”).  

⚠️ **Importante:**  
Cada pessoa deve usar **sua própria chave**.  
Nunca compartilhe sua **API Key** publicamente ou a inclua no código-fonte.

---

## ▶️ Executando o Projeto

Com tudo configurado, basta executar o comando:
```bash
streamlit run assistente.py
```

Isso abrirá automaticamente o navegador em:
👉 http://localhost:8501

---

## 💬 Exemplo de Uso

**👩 Usuário:**  
> Como faço um loop `for` em Python?  

**🤖 Nati | AI Coder:**  
> Claro! O loop `for` em Python é usado para iterar sobre sequências...

---

## 🧠 Como o Assistente Funciona

O arquivo `assistente.py` segue uma arquitetura simples e clara:

1. **Interface Streamlit:** Cria o layout, a barra lateral e a área de chat;  
2. **Input da API Key:** O usuário insere sua chave Groq manualmente;  
3. **Gerenciamento de Sessão:** `st.session_state` guarda o histórico da conversa;  
4. **Envio de Mensagens:** O prompt do usuário e as instruções do sistema são enviados ao modelo;  
5. **Resposta do Modelo:** A IA responde com explicação, exemplo de código e link de documentação;  
6. **Exibição Dinâmica:** O Streamlit atualiza o chat em tempo real.

---

## 🧭 Próximos Passos

- 💾 Implementar cache de respostas;  
- 🧩 Adicionar suporte a outras linguagens além de Python;  
- 🌐 Publicar a aplicação no **Streamlit Cloud**;  
- 🧰 Integrar com banco de dados para armazenar histórico.

---

## 👩‍💻 Autora

**Natália Guarnieri**  
Profissional de Dados e Exploradora de IA 🤖  
📍 Brasil  

🔗 [LinkedIn](https://www.linkedin.com/in/nataliaguarnieri)  
🔗 [Portfólio no GitHub](https://github.com/nataliaguarnieri)

---

✨ Projeto desenvolvido como parte do meu **portfólio de IA + Engenharia de Dados**, unindo tecnologia, aprendizado e criatividade.  
Feito com 💜 e curiosidade por **Natália Guarnieri**. 