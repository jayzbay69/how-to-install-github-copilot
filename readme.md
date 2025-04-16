<p align="center">
<img src="./assets/github-copilot.png" style="border-radius:2rem;" alt="GitHub Copilot" width="150" /> <br /> <b>Guia para Instalação e Configuração do GitHub Copilot no VS Code</b> <br /> <sub><sup><b>(how-to-install-github-copilot)</b></sup></sub> <br /> </p> 
<p align="center"> Este projeto é um guia detalhado para instalar, configurar e utilizar o GitHub Copilot no Visual Studio Code. Ele abrange desde os pré-requisitos até dicas de uso, atalhos e solução de problemas. <br /> </p>

<p align="center"> This project is a detailed guide for installing, configuring, and using GitHub Copilot in Visual Studio Code. It covers everything from prerequisites to usage tips, shortcuts, and troubleshooting. <br /> </p>

---

<details> <summary>🇧🇷 Detalhes do Projeto (Português)</summary>

## Resumo do Projeto

Este guia foi desenvolvido para auxiliar na instalação e configuração do GitHub Copilot no Visual Studio Code. Ele fornece instruções passo a passo para ativar o Copilot, personalizar suas configurações e solucionar problemas comuns.

---

## Funcionalidades

- **Instalação do GitHub Copilot**: Guia para instalar e autenticar a extensão no VS Code.
- **Configuração Personalizada**: Instruções para ajustar as preferências do Copilot.
- **Atalhos de Teclado**: Lista de comandos úteis para interagir com o Copilot.
- **GitHub Copilot Chat**: Orientações para usar o chat interativo com IA.
- **Solução de Problemas**: Dicas para resolver erros comuns.

---

## Tecnologias e Ferramentas Utilizadas

- **GitHub Copilot**: Extensão de IA para autocompletar código.
- **Visual Studio Code**: Editor de código utilizado para integração com o Copilot.

---

# 🚀 Como Instalar e Configurar o GitHub Copilot no VS Code

## ✅ Pré-requisitos

Antes de instalar o GitHub Copilot, verifique se você possui:

1. **Conta no GitHub**  
   → [Crie aqui](https://github.com/join)

2. **Assinatura ativa do GitHub Copilot**  
   → [Ative aqui](https://github.com/features/copilot)  
   💡 *Estudantes podem obter acesso gratuito com o [GitHub Student Pack](https://education.github.com/pack)*

3. **Visual Studio Code instalado**  
   → [Baixar VS Code](https://code.visualstudio.com/)

---

## 🧩 Instalação do GitHub Copilot no VS Code

1. Abra o **Visual Studio Code**
2. Acesse a aba de extensões (`Ctrl + Shift + X`)
3. Pesquise por **GitHub Copilot**
4. Clique em **Install** na extensão oficial
5. Após instalar, clique em **Sign In** para autenticar com sua conta do GitHub
6. Autorize o acesso no navegador e volte ao VS Code

---

## ⚙️ Configuração do GitHub Copilot

### 🔧 Configurações básicas:

1. Vá em: `File` → `Preferences` → `Settings` (ou `Ctrl + ,`)
2. Pesquise por **Copilot**
3. Personalize as opções:

- `Copilot: Enable` → Ativa/desativa o Copilot
- `Copilot: Inline Suggestions` → Ativa sugestões no meio do código
- `Copilot: Show Editor Completions` → Sugestões no estilo Intellisense

---

## 🧠 Como Usar

Durante a escrita de código:

- Sugestões aparecem em **cinza claro**
- Para **aceitar**: pressione `Tab`
- Para **rejeitar**: continue digitando ou pressione `Esc`
- Para **navegar entre sugestões**: use `Alt + [` e `Alt + ]`

---

## ⚙️ Comandos Úteis do GitHub Copilot no VS Code

### 💻 Atalhos de Teclado (Windows/Linux)

| Ação                                 | Atalho           |
|--------------------------------------|------------------|
| Aceitar sugestão                     | `Tab`            |
| Rejeitar sugestão                    | `Esc`            |
| Ver próxima sugestão                 | `Alt + ]`        |
| Ver sugestão anterior                | `Alt + [`        |
| Abrir painel de sugestões            | `Ctrl + Enter`   |
| Abrir/fechar paleta de comandos      | `Ctrl + Shift + P` |
| Ativar/desativar sugestões inline    | `Alt + \`        |
| Iniciar nova conversa (Copilot Chat) | `Ctrl + Shift + I` |

---

### 🍏 Atalhos no macOS

| Ação                                 | Atalho           |
|--------------------------------------|------------------|
| Aceitar sugestão                     | `Tab`            |
| Rejeitar sugestão                    | `Esc`            |
| Ver próxima sugestão                 | `Option + ]`     |
| Ver sugestão anterior                | `Option + [`     |
| Abrir painel de sugestões            | `Cmd + Enter`    |
| Ativar/desativar sugestões inline    | `Option + \`     |
| Iniciar nova conversa (Copilot Chat) | `Cmd + Shift + I` |

---

### 🎛️ Comandos da Paleta (Ctrl + Shift + P)

Digite esses comandos na paleta do VS Code para interagir com o Copilot:

| Comando                                                | Descrição                            |
|---------------------------------------------------------|----------------------------------------|
| `> GitHub Copilot: Enable`                              | Ativa o Copilot                        |
| `> GitHub Copilot: Disable`                             | Desativa o Copilot                     |
| `> GitHub Copilot: Toggle Copilot`                      | Liga/desliga o Copilot                 |
| `> GitHub Copilot: Open Copilot`                        | Abre o painel lateral do Copilot       |
| `> GitHub Copilot: Reset Copilot`                       | Reinicia a extensão                    |
| `> GitHub Copilot: Show Copilot Output`                 | Mostra o log de saída do Copilot       |
| `> GitHub Copilot Chat: Chat with GitHub`               | Abre o chat interativo com IA          |
| `> GitHub Copilot Chat: Explain this code`              | Analisa o código selecionado           |
| `> GitHub Copilot Chat: Help me fix this`               | Sugere correções para erros            |
| `> GitHub Copilot Chat: Generate unit tests`            | Gera testes automatizados              |
| `> GitHub Copilot Chat: Provide feedback`               | Envia feedback sobre o Copilot         |

---

## 📄 Exemplo de Uso

Prompt: `Crie uma função para calcular vetorial em Python`

Resultado:

```python
# Função para calcular fatorial
def fatorial(n):
    if n == 0:
        return 1
    else:
        return n * fatorial(n-1)
```

## 🧪 Dicas e Boas Práticas

- Use comentários descritivos
- Mantenha boas práticas de codificação
- Sempre valide o código sugerido

## 💡 Dica Bônus: GitHub Copilot Chat

Você também pode conversar com o Copilot direto no VS Code!

Para isso:
- Instale a extensão "GitHub Copilot Chat"
- Use Ctrl + Shift + P e busque por Copilot Chat: Chat with GitHub
- Pergunte sobre trechos de código, erros, refatoração, etc.

## 🔴 Solução de Problemas Comuns

### ❌ Copilot não aparece?

- Verifique se a extensão está instalada corretamente.
- Reinicie o VS Code.
- Confira se sua assinatura está ativa em GitHub Copilot.

### ❌ Sugestões não funcionam?

- Verifique sua conexão com a internet.
- Tente desativar e reativar a extensão.

---

</details>

<details> <summary>🇺🇸 Project Details (English)</summary>

## Project Summary

This guide was developed to assist in installing and configuring GitHub Copilot in Visual Studio Code. It provides step-by-step instructions to activate Copilot, customize its settings, and troubleshoot common issues.

---

## Features

- **GitHub Copilot Installation**: Guide to install and authenticate the extension in VS Code.
- **Custom Configuration**: Instructions to adjust Copilot preferences.
- **Keyboard Shortcuts**: List of useful commands to interact with Copilot.
- **GitHub Copilot Chat**: Guidance to use the interactive AI chat.
- **Troubleshooting**: Tips to resolve common errors.

---

## Technologies and Tools Used

- **GitHub Copilot**: AI-powered code completion extension.
- **Visual Studio Code**: Code editor used for Copilot integration.

---

# 🚀 How to Install and Configure GitHub Copilot in VS Code

## ✅ Prerequisites

Before installing GitHub Copilot, ensure you have:

1. **GitHub Account**  
   → [Create here](https://github.com/join)

2. **Active GitHub Copilot Subscription**  
   → [Activate here](https://github.com/features/copilot)  
   💡 *Students can get free access with the [GitHub Student Pack](https://education.github.com/pack)*

3. **Visual Studio Code Installed**  
   → [Download VS Code](https://code.visualstudio.com/)

---

## 🧩 Installing GitHub Copilot in VS Code

1. Open **Visual Studio Code**
2. Go to the Extensions tab (`Ctrl + Shift + X`)
3. Search for **GitHub Copilot**
4. Click **Install** on the official extension
5. After installation, click **Sign In** to authenticate with your GitHub account
6. Authorize access in the browser and return to VS Code

---

## ⚙️ Configuring GitHub Copilot

### 🔧 Basic Settings:

1. Go to: `File` → `Preferences` → `Settings` (or `Ctrl + ,`)
2. Search for **Copilot**
3. Customize the options:

- `Copilot: Enable` → Enable/disable Copilot
- `Copilot: Inline Suggestions` → Enable inline code suggestions
- `Copilot: Show Editor Completions` → IntelliSense-style suggestions

---

## 🧠 How to Use

While writing code:

- Suggestions appear in **light gray**
- To **accept**: press `Tab`
- To **reject**: keep typing or press `Esc`
- To **navigate between suggestions**: use `Alt + [` and `Alt + ]`

---

## ⚙️ Useful GitHub Copilot Commands in VS Code

### 💻 Keyboard Shortcuts (Windows/Linux)

| Action                               | Shortcut         |
|--------------------------------------|------------------|
| Accept suggestion                    | `Tab`            |
| Reject suggestion                    | `Esc`            |
| View next suggestion                 | `Alt + ]`        |
| View previous suggestion             | `Alt + [`        |
| Open suggestions panel               | `Ctrl + Enter`   |
| Open/close command palette           | `Ctrl + Shift + P` |
| Enable/disable inline suggestions    | `Alt + \`        |
| Start a new conversation (Copilot Chat) | `Ctrl + Shift + I` |

---

### 🍏 Shortcuts on macOS

| Action                               | Shortcut         |
|--------------------------------------|------------------|
| Accept suggestion                    | `Tab`            |
| Reject suggestion                    | `Esc`            |
| View next suggestion                 | `Option + ]`     |
| View previous suggestion             | `Option + [`     |
| Open suggestions panel               | `Cmd + Enter`    |
| Enable/disable inline suggestions    | `Option + \`     |
| Start a new conversation (Copilot Chat) | `Cmd + Shift + I` |

---

### 🎛️ Command Palette (Ctrl + Shift + P)

Type these commands in the VS Code command palette to interact with Copilot:

| Command                                                | Description                            |
|---------------------------------------------------------|----------------------------------------|
| `> GitHub Copilot: Enable`                              | Enables Copilot                        |
| `> GitHub Copilot: Disable`                             | Disables Copilot                       |
| `> GitHub Copilot: Toggle Copilot`                      | Toggles Copilot on/off                 |
| `> GitHub Copilot: Open Copilot`                        | Opens the Copilot side panel           |
| `> GitHub Copilot: Reset Copilot`                       | Resets the extension                   |
| `> GitHub Copilot: Show Copilot Output`                 | Displays the Copilot output log        |
| `> GitHub Copilot Chat: Chat with GitHub`               | Opens the interactive AI chat          |
| `> GitHub Copilot Chat: Explain this code`              | Analyzes the selected code             |
| `> GitHub Copilot Chat: Help me fix this`               | Suggests fixes for errors              |
| `> GitHub Copilot Chat: Generate unit tests`            | Generates automated tests              |
| `> GitHub Copilot Chat: Provide feedback`               | Sends feedback about Copilot           |

---

## 📄 Example Usage

Prompt: `Create a function to calculate factorial in Python`

Result:

```python
# Function to calculate factorial
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

## 🧪 Tips and Best Practices

- Use descriptive comments
- Follow good coding practices
- Always validate the suggested code

---

## 💡 Bonus Tip: GitHub Copilot Chat
You can also chat with Copilot directly in VS Code!

To do this:
- Install the "GitHub Copilot Chat" extension
- Use Ctrl + Shift + P and search for Copilot Chat: Chat with GitHub
- Ask about code snippets, errors, refactoring, etc.

## 🔴 Common Troubleshooting

### ❌ Copilot not showing up?
- Check if the extension is installed correctly.
- Restart VS Code.
- Ensure your GitHub Copilot subscription is active.

### ❌ Suggestions not working?
- Check your internet connection.
- Try disabling and re-enabling the extension.

</details>

---

## License

This software is licensed under the terms of the **MIT License**.

---

<div align="center">

Developed by [Vitor Bittencourt](https://linktr.ee/vv_bittencourt) ☕

</div>