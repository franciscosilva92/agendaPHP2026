# 📅 Agenda Eletrônica com PHP e PDO

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![AdminLTE](https://img.shields.io/badge/AdminLTE-3C8DBC?style=for-the-badge&logo=bootstrap&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

> Solução web desenvolvida em **PHP procedural com PDO** para o gerenciamento seguro e eficiente de contatos pessoais. Construída sobre o tema **AdminLTE**, entrega uma interface moderna, intuitiva e responsiva para o dia a dia.

---

## 📋 Índice

- [🎯 Recursos Principais](#-recursos-principais)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📸 Preview](#-preview)
- [🚀 Como Instalar no Servidor Local](#-como-instalar-no-servidor-local)
- [📄 Licença](#-licença)

---

## 🎯 Recursos Principais

- **🔐 Autenticação e Segurança**
  - **Login e Cadastro:** Fluxo simples e direto para criação e acesso de contas.
  - **Proteção de Dados:** Armazenamento seguro com senhas criptografadas.

- **📇 Gerenciamento de Contatos**
  - **Privacidade Individual:** Cada usuário visualiza e gerencia apenas a sua própria lista de contatos.
  - **CRUD Completo:** Cadastre, edite, visualize e exclua contatos (nome, telefone e e-mail) com facilidade.

- **👤 Perfil Personalizável**
  - **Gestão de Conta:** Atualização completa dos dados cadastrais, incluindo upload e troca de foto de perfil.

- **📊 Relatórios e Exportações**
  - **Tabelas Dinâmicas:** Listagem avançada com paginação, ordenação e busca instantânea via **DataTables**.
  - **Exportação de Dados:** Gere relatórios em **PDF** ou exporte sua agenda para **planilhas** com um clique.

---

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia / Ferramenta | Descrição |
| :--- | :--- | :--- |
| **Backend** | PHP (Procedural) + PDO | Lógica de negócio e comunicação segura contra SQL Injection |
| **Banco de Dados** | MySQL | Armazenamento relacional de usuários e contatos |
| **Frontend** | HTML5, CSS3, JavaScript | Estruturação e interatividade das páginas |
| **Template / UI** | [AdminLTE](https://adminlte.io/) | Painel administrativo responsivo baseado em Bootstrap |
| **Tabelas** | DataTables | Filtragem, paginação e exportação de dados |

---

## 📸 Preview

> [!TIP]
> **Dica:** Adicione aqui capturas de tela da tela de login e do painel principal (ex: `![Tela Principal](assets/img/preview.png)`) para valorizar ainda mais o projeto no GitHub.

---

## 🚀 Como Instalar no Servidor Local

### Pré-requisitos

Certifique-se de ter um ambiente de servidor local instalado (com Apache, PHP e MySQL), como:
- [XAMPP](https://www.apachefriends.org/)
- [WAMP](https://www.wampserver.com/)
- [MAMP](https://www.mamp.info/)

### Passo a passo

1. **Clone o repositório** para a pasta pública do seu servidor (`htdocs` no XAMPP ou `www` no WAMP):

   ```bash
   https://github.com/franciscosilva92/agendaPHP2026.git
   ```

2. **Configure o banco de dados:**
   - Inicie os serviços **Apache** e **MySQL** no painel do seu servidor local.
   - Acesse o **phpMyAdmin** em `http://localhost/phpmyadmin`.
   - Crie um novo banco de dados (ex: `agenda_db`).
   - Selecione o banco criado, vá na aba **Importar** e carregue o arquivo `new_agenda.sql` localizado na raiz do projeto.

3. **Configure a conexão com o banco:**
   - Abra o arquivo `config.php` e ajuste as credenciais conforme o seu ambiente:

   ```php
   <?php
   // Exemplo de configuração no config.php
   define('HOST', 'localhost');
   define('DBNAME', 'agenda_db');
   define('USER', 'root');
   define('PASS', '');
   ```

4. **Acesse o sistema:**
   - Abra o navegador e acesse:
     ```text
     http://localhost/agendaPHP2026
     ```

> [!NOTE]
> Caso tenha renomeado a pasta do projeto durante o clone, substitua `agendaPHP2026` na URL pelo nome da pasta correspondente.

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

> A licença MIT permite o uso, cópia, modificação e distribuição gratuita deste software, desde que o aviso de copyright original seja mantido. O software é fornecido "como está", sem garantias de qualquer tipo.

---

<p align="center">
  Desenvolvido por <a href="https://github.com/franciscosilva92">Leandro Costa</a>
</p>
