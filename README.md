# Template WordPress para Energy Inversores

Este projeto é um **template WordPress para Energy Inversores**

## 🚀 Recursos
- **WordPress** serve como CMS com os plugins ACF e Safe SVG.
- **SASS** para estilização, tornando o CSS mais organizado e fácil de manter.

## 🛠️ Requisitos
Para executar este projeto, certifique-se de que você tem o seguinte:

- **Node.js**: Versão 16 ou superior
- **PHP**: Versão 7.4 ou superior
- **WordPress**: Versão mais recente. Testado na versão 6.7.2
- **MySQL**: Banco de dados para o WordPress

## 📦 Instalação
### 0. Crie as pastas necessárias

### 1. Instalação WordPress
- Baixe a versão mais recente do WordPress.
- Extraia-a para seu diretório backend.
- Configure o arquivo wp-config.php com suas credenciais de banco de dados.

``
### 2. Install WordPress Plugins
- **ACF (Advanced Custom Fields)**: Para criar campos de conteúdo personalizados dentro do WordPress.
- **Safe SVG**: Permite o upload e uso seguros de arquivos SVG no WordPress.
- **Contact Form 7**: Para criar formulários de contato.
- **WP Mail SMTP**: Para configurar as definições de SMTP para envio de e-mails.

Você pode instalar esses plugins diretamente pelo painel administrativo do WordPress ou baixá-los e colocá-los no diretório `wp-content/plugins`.

- Ative o tema e todos os plugins necessários.

### 5. Execute o Projeto

````bash
cd wp-content/themes/energyinversores
npm install
npm run dev