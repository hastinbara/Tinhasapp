Baratinhas.com.br – App Operacional Interno

  

> Portal de entrada para o sistema operacional interno do Baratinhas.com.br.




---

🎯 Visão Geral

Este projeto consiste em um aplicativo Android e um portal web, desenvolvido para uso exclusivo da equipe interna do Baratinhas.com.br. Funcionalidades principais:

App Android: feito no AppSheet integrado ao WebView do site interno.

Portal Web ADM: acesso e monitoramento via painel em baratinhas.com.br/ADM.

Distribuição: APK disponível em Google Drive, QR code para instalação.



---

📱 Instalação e Acesso

Android (APK)

1. Escaneie o QR code abaixo ou acesse a pasta do Drive:

<!-- Substitua pela URL do QR gerada -->


2. Baixe o APK mais recente na Pasta de Instalação.


3. Permita instalações de fontes externas no seu dispositivo.



Web (Portal ADM)

Navegue até: baratinhas.com.br/ADM

Login com credenciais corporativas (SSO/LDAP).



---

🏗️ Estrutura do Projeto

/ (root)
├── appsheet/               # Configurações e metadados do AppSheet
├── web/                    # Código do portal ADM (HTML, CSS, JS)
├── android/                # Gerador e configuração de APK
│   └── build.gradle        # Config Android
└── README.md               # Este arquivo


---

⚙️ Tecnologias e Ferramentas

AppSheet: construído como PWA para facilitar deploy e manutenção.

Android WebView: container do AppSheet dentro de APK.

HTML5 / CSS3 / JS: portal de administração.

Google Drive: distribuição de APK.

GitHub Actions: CI para validar builds Android.



---

🛠️ Guia de Desenvolvimento

1. Clonar repositório:

git clone https://github.com/hastinbara/Tinhasapp.git
cd Tinhasapp


2. Configurar AppSheet:

Abra o editor AppSheet vinculado a este repositório.

Atualize tabelas e colunas conforme o schema do sistema interno.



3. Build Android:

cd android
./gradlew assembleRelease


4. Deploy Web:

Suba arquivos da pasta web/ no servidor ou serviço de hosting.





---

🚀 Como Contribuir

Abra issues para bugs ou sugestões.

Crie pull requests direcionados à branch develop.

Siga o guia de estilo definido em .editorconfig.



---

📫 Contato

Para dúvidas ou suporte interno, contate:

Equipe de TI Baratinhas: ti@baratinhas.com.br

Slack interno: canal #adm-app



---

> Made with ❤️ by the Aloj Team.



