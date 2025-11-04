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
A seguir está o guia completo para rodar o Nati | AI Coder na sua máquina, mesmo que você nunca tenha usado Python ou Streamlit antes.

### 1️⃣ Clone este repositório
Esse passo serve para baixar o projeto do GitHub para o seu computador.

💡 “Clonar” significa criar uma cópia local do projeto, onde você poderá abrir e rodar os arquivos.

Abra o Prompt de Comando (Windows) ou o Terminal (Mac/Linux) e execute:
```bash
git clone https://github.com/nataliaguarnieri/portfolio-ia-projects/proj_1_AI_Coder.git
cd proj_1_AI_Coder
```

📁 Isso vai criar uma pasta chamada proj_1_AI_Coder e entrar nela.

Se você não tiver o Git instalado, baixe em:
👉 https://git-scm.com/downloads

### 2️⃣ Crie e ative um ambiente virtual
O ambiente virtual é um espaço isolado do Python, usado para instalar as dependências do projeto sem interferir em outros programas do seu computador.

No terminal, digite:
```bash
python -m venv venv
```
Isso cria uma pasta chamada venv com tudo que o Python precisa para o projeto.

Agora, ative o ambiente virtual:
* **Windows:**
```bash
venv\Scripts\activate
```
* **Mac/Linux:**
```bash
source venv/bin/activate
```
💡 Quando ativado, você verá algo como (venv) aparecendo antes do cursor no terminal — isso indica que o ambiente virtual está ativo.

### 3️⃣ Instale as dependências
As dependências são as bibliotecas que o projeto precisa para funcionar (como Streamlit, Groq, etc.).

Com o ambiente virtual ativo, rode:
```bash
pip install -r requirements.txt
```
Esse comando lê o arquivo requirements.txt e instala automaticamente todas as bibliotecas necessárias.
Isso pode levar alguns minutos.

---

## 🔑 Configurando sua API Key da Groq

A API Key é a sua chave pessoal de acesso à IA usada no projeto.
Ela permite que o app se comunique com o modelo de linguagem hospedado na Groq.

Para gerar a sua chave:

1. Acesse 👉 [https://console.groq.com/keys](https://console.groq.com/keys)
2. Crie uma conta gratuita (caso ainda não tenha);
3. Clique em “Create API Key”;  
4. Copie o código gerado (algo como gsk_12345abc...).

🔐 **Onde inserir a chave:**
* Quando abrir o app, haverá um campo na barra lateral escrito “Insira sua API Key Groq”.
* Cole sua chave lá e clique em Enviar.

⚠️ **Importante:**
* Essa chave é pessoal — não compartilhe publicamente nem salve no código.
* Se você perder ou suspeitar de uso indevido, gere uma nova no painel da Groq.

---

## ▶️ Executando o Projeto

Agora vem a parte divertida: rodar o assistente!

No terminal (com o ambiente ainda ativo), digite:
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
