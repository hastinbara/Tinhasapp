[![Download APK](https://img.shields.io/badge/Download-APK-blue)](https://drive.google.com/drive/folders/1W5ljF4630OmE-y0rmSBOP-Gp64h9W4At)
[![Site Oficial](https://img.shields.io/badge/Visite-Baratinhas.com.br-red)](Baratinhas.com.br/adm)

# 🪳 Baratinhas.com.br – App Operacional Interno

> Portal de entrada para o sistema operacional interno do Baratinhas.com.br.

---

## 🎯 Visão Geral

Este projeto consiste em um **aplicativo Android** e um **portal web**, desenvolvidos para **uso exclusivo da equipe interna** do Baratinhas.com.br.

- 📱 **App Android**: criado no AppSheet e empacotado com WebView.
- 💻 **Portal Web ADM**: acesso via [baratinhas.com.br/ADM](https://baratinhas.com.br/ADM)
- 📦 **Distribuição do APK**: disponível via Google Drive.

---

## 📱 Instalação e Acesso

### Android (APK)

1. Acesse a pasta do Drive com os instaladores:
   👉 [Abrir Pasta de Instalação (Google Drive)](https://drive.google.com/drive/folders/1W5ljF4630OmE-y0)

2. Baixe o arquivo `APK` mais recente.

3. No celular, vá em **Configurações > Segurança** e ative **Fontes desconhecidas** para permitir a instalação.

---

### Web (Portal ADM)

- Acesse: [https://baratinhas.com.br/ADM](https://baratinhas.com.br/ADM)
- Faça login com suas credenciais corporativas (SSO ou LDAP).

---

## 🏗️ Estrutura do Projeto

/ ├── appsheet/         # Configurações e metadados do AppSheet ├── web/              # Código do portal ADM (HTML, CSS, JS) ├── android/          # Gerador e configuração do APK │   └── build.gradle └── README.md         # Este arquivo

---

## ⚙️ Tecnologias Utilizadas

- **AppSheet** – base do app operacional, formato PWA.
- **Android WebView** – contêiner nativo para o AppSheet.
- **HTML5 / CSS3 / JS** – estrutura do portal administrativo.
- **Google Drive** – hospedagem e distribuição do APK.
- **GitHub Actions** – integração contínua para builds.

---

## 🛠️ Guia de Desenvolvimento

### 1. Clonar o repositório:

```bash
git clone https://github.com/hastinbara/Tinhasapp.git
cd Tinhasapp

2. Configurar o AppSheet:

Acesse o editor do AppSheet conectado ao projeto.

Verifique se as tabelas estão atualizadas conforme o schema atual.


3. Gerar o APK:

cd android
./gradlew assembleRelease

4. Deploy do Portal Web:

Envie os arquivos da pasta web/ para o seu servidor ou serviço de hosting.



---

🚀 Como Contribuir

Abra uma issue para reportar bugs ou sugerir melhorias.

Faça um pull request para a branch develop.

Siga o guia de estilo definido no .editorconfig.



---

📫 Contato

📧 Equipe de TI Baratinhas: ti@baratinhas.com.br

💬 Slack interno: canal #adm-app



---

> Feito com ❤️ pelo time Aloj.

