
# IA Assistente de Textos ✍️

Um assistente de escrita poderoso construído com React e a API do Google Gemini. Este projeto ajuda usuários a corrigir, aprimorar e gerar textos de forma inteligente.

🔗 **[Clique aqui para testar a versão online!](https://ia-assist-frontend.vercel.app/)**

## ✨ Funcionalidades

- **Correção Gramatical:** Corrige erros de ortografia e gramática.
- **Aprimoramento de Tom:** Reescreve textos para soarem mais profissionais.
- **Expansão de Ideias:** Continua um texto a partir de uma ideia inicial.
- **Busca por Sinônimos:** Sugere alternativas para palavras e expressões.
- **Busca por Significado:** Explica o significado de um termo como um dicionário.
- **Tema Claro e Escuro:** Interface adaptável com um clique.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **API de IA:** Google Gemini
- **Hospedagem:** Vercel (Frontend) e Render (Backend)

## 🚀 Como Executar Localmente

### Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### Configure o Backend:

```bash
cd assistente-backend
npm install
# Crie um arquivo .env e adicione sua GEMINI_API_KEY
echo "GEMINI_API_KEY=SUA_CHAVE_AQUI" > .env
node index.js
```

### Configure o Frontend (em um novo terminal):

```bash
cd assistente-frontend
npm install
npm start
```
