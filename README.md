# 📁 Projeto Integrador - Sistema de Cadastro: "Last Seven"

Este repositório contém o código-fonte e a estrutura do projeto **Last Seven**, um site desenvolvido como parte do Projeto Integrador do curso técnico em Informática (SENAC - Porto Velho, RO). O sistema tem como objetivo o **cadastro de usuários e gerenciamento de contatos** de clientes que solicitam serviços de programação.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estruturação das páginas web  
- **CSS3** - Estilização e responsividade  
- **JavaScript** - Validações e interações na interface  
- **PHP** - Backend e integração com banco de dados  
- **MySQL** - Banco de dados relacional  
- **Java (Swing + JDBC)** - Aplicação desktop para leitura e gerenciamento dos cadastros  

---

## 💡 Funcionalidades

### Site Web
- Página Home com apresentação da empresa
- Página Portfólio com os serviços oferecidos
- Página de Contato com formulário de cadastro
- Envio dos dados do formulário para o banco de dados MySQL
- Validação de campos com JavaScript

### Backend (PHP)
- Processamento do formulário
- Conexão com banco de dados
- Inserção de dados no MySQL com segurança (PDO)

### Aplicação Desktop (Java)
- Consulta ao banco de dados via JDBC
- Listagem de cadastros realizados
- Atualização e gerenciamento de status dos cadastros

---

## 🧱 Estrutura de Diretórios

```bash
/
├── index.html
├── portfólio.html
├── contato.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── php/
│   └── conectar.php
│   └── processar_formulario.php
├── sql/
│   └── lastseven_db.sql
├── java/
│   └── AplicativoDesktop.java
└── README.md
```

---

## 📂 Banco de Dados

- Nome: `lastseven_db`
- Tabela: `cadastros`
- Campos: `id`, `nome`, `email`, `servico`, `mensagem`, `status`, `data_envio`

O script para criação do banco está na pasta `sql/`.

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/last-seven.git
   ```

2. Importe o banco de dados MySQL com o arquivo `lastseven_db.sql`.

3. Configure os dados de conexão no arquivo `php/conectar.php`.

4. Inicie um servidor local (como XAMPP, WAMP ou PHP Server) e abra o `index.html` no navegador.

5. Para usar o aplicativo Java:
   - Compile e execute `AplicativoDesktop.java`
   - Certifique-se de que o banco esteja rodando e com as credenciais corretas

---

## 👥 Equipe

- Adaiana Duarte (Scrum Master / Planejamento)
- Vinícius Moreira (Front-End & Back-End)
- Eduarda Pinheiro (Validação & Testes)
- Kléber Lucas (Banco de Dados)
- Gean Greguy (Banco de Dados)
- Nicholas Bollate (Documentação)
- João Silva (Documentação)

---

## 📜 Licença

Este projeto é apenas para fins educacionais e não possui fins comerciais.