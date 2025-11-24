

#  Python e Gemini: chatbot com IA Generativa

<h2>🧠 Sobre o projeto</h2>

<p>Um chatbot inteligente que integra a <b>API Gemini</b> com um backend em <b>Python + Flask</b> e uma interface leve em <b>HTML, CSS e JavaScript</b>. <br> Projetado para oferecer respostas em tempo real e enriquecer a experiência com dados estruturados em <b>CSV</b>, permitindo interações mais contextualizadas e precisas.</p>

## 🚀 Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white&style=for-the-badge)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?logo=google&logoColor=white&style=for-the-badge)
![CSV](https://img.shields.io/badge/CSV-4CAF50?logo=microsoft-excel&logoColor=white&style=for-the-badge)

<h2>🧩 Arquitetura do Projeto</h2>

<pre>
<span style="color:#58a6ff; font-weight:bold;">gemini-node/</span>
|
|-- <span style="color:#d2a8ff;">app/</span>
|   |-- <span style="color:#a5d6ff;">app.js</span>
|   |-- <span style="color:#a5d6ff;">chat.js</span>
|   |-- <span style="color:#a5d6ff;">embedding.js</span>
|   |-- <span style="color:#a5d6ff;">inicializaChat.js</span>
|   `-- <span style="color:#a5d6ff;">package.json</span>
|
|-- <span style="color:#d2a8ff;">static/</span>
|   |-- <span style="color:#d2a8ff;">css/</span>
|   |-- <span style="color:#d2a8ff;">img/</span>
|   `-- <span style="color:#d2a8ff;">js/</span>
|
|-- <span style="color:#d2a8ff;">templates/</span>
|
|-- <span style="color:#a5d6ff;">package-lock.json</span>
|-- <span style="color:#a5d6ff;">Pacotes_Argentina.csv</span>
|-- <span style="color:#a5d6ff;">Pacotes_EUA.csv</span>
|-- <span style="color:#a5d6ff;">Politicas.csv</span>
`-- <span style="color:#8b949e;">README.md</span>
</pre>


<h2>🛠️ Como Rodar Localmente</h2>

Após baixar o projeto, você pode abrir com Visual Studio Code. Em seguida, é necessário que você prepare seu ambiente. Para isso:

```bash
python -m venv venv-gemini-2
source venv-gemini-2/Scripts/activate
```

Em seguida, instale os pacotes utilizando:

```bash
pip install -r requirements.txt
```

Gerar API_KEY e associar ao .env:

```bash
GEMINI_API_KEY = "SUA_CHAVE_AQUI"
```

<h2>📜 Licença</h2>
Distribuído sob licença MIT.

<h2>👤 Autor</h2>
Emilly Caroline de Lima Pereira (emyzdk)
🔗 GitHub: https://github.com/emyzdk
