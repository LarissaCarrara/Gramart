# Gramart
🚀 Professor de Português AI: Dominando a Gramática com Inteligência Artificial!

Este repositório apresenta uma ferramenta inovadora que utiliza a inteligência artificial Gemini (Google) para facilitar o ensino e a compreensão da análise sintática da língua portuguesa de forma clara, acessível e didática.

📚 Guia de Gramática AI
Uma aplicação prática e interativa para estudar gramática e análise sintática. Basta fornecer uma frase em português e a ferramenta identifica todos os elementos da estrutura da oração, como sujeito, predicado, verbos, complementos e muito mais — tudo com explicações curtas e fáceis de entender.

🧠 Funcionamento
A ferramenta é desenvolvida com Google Gemini e Google ADK. Todo o processo de análise acontece dentro do próprio modelo de IA, sem depender de buscas externas. O modelo reconhece as estruturas gramaticais da língua portuguesa e fornece uma análise sintática detalhada e organizada.

🛠️ Como Usar
**Pré-requisitos:**
- Python 3.8+
- Conta no Google Cloud com acesso à API do Gemini

**Configuração da API:**
- Obtenha uma chave no [Google AI Studio](https://aistudio.google.com/app/apikey)
- No Colab: use `userdata.get()` e armazene como `"GOOGLE_API_KEY"`
- Localmente:
  - Linux/macOS:  
    `export GOOGLE_API_KEY="SUA_CHAVE_AQUI"`
  - Windows (Prompt de Comando):  
    `set GOOGLE_API_KEY="SUA_CHAVE_AQUI"`
  - Windows (PowerShell):  
    `$env:GOOGLE_API_KEY="SUA_CHAVE_AQUI"`

**Instalação:**
```bash
git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_SEU_REPOSITORIO>
pip install google-genai google-adk


