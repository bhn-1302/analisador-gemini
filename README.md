# 🧠 Analisador de Código com IA (Gemini)

Este projeto é um analisador de código alimentado pela API Gemini do Google. Desenvolvido com **React + Vite**, o aplicativo permite ao usuário colar ou escrever um trecho de código e receber uma análise rápida e didática com sugestões de melhorias, detecção de possíveis erros e boas práticas recomendadas.

## 🔍 Demonstração

<img src="./src/images/gif-api-gemini.gif" alt="demonstração do projeto em funcionamento">

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/) com **Hooks**
- [Vite](https://vitejs.dev/) para bundling e desenvolvimento rápido
- [Gemini API](https://ai.google.dev/) da Google para análise com IA
- Ambiente com variáveis seguras via `.env.local`

## ⚙️ Funcionalidades

- Interface interativa para escrever, colar e analisar códigos (HTML, CSS, JavaScript, etc)
- Retorno estruturado da IA com:
  - **Principais problemas detectados**
  - **Soluções diretas e concisas**
  - **Sugestões de boas práticas**
- Exibição de mensagens de erro e loading durante a requisição

## 💡 Aprendizados

Durante o desenvolvimento deste projeto, aprendi e pratiquei:

- Criação de **componentes funcionais reutilizáveis**
- Uso de **React Hooks** (`useState`)
- Consumo de **APIs externas com async/await**
- Armazenamento seguro de chaves via `.env.local`
- Criação de **prompts personalizados** para guiar respostas da IA

## 📦 Como executar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/analisador-gemini.git

# Acesse a pasta do projeto
cd analisador-gemini

# Instale as dependências
npm install

# Crie o arquivo de variáveis de ambiente
touch .env.local

No arquivo .env.local, adicione sua chave da API Gemini:
VITE_GEMINI_API_KEY=sua-chave-aqui

Depois, inicie o projeto:
npm run dev
```

## 🧑‍💻 Autor

Desenvolvido por Brenno Henrique do Nascimento 💙

Entre em contato para sugestões ou melhorias!