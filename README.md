# FitAlert - API

---

## 📦 Sobre o Projeto

O FitAlert é um sistema de monitoramento de fluxo em provadores de roupa. Nosso objetivo é monitorar entrada e saída dos clientes para armazenar dados de data e horário, gerar alertas e posteriormente entregar uma dashboard completa para auxiliar na tomada de decisão estratégica.

---

## 🛠 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- HTML5
- JavaScript (Vanilla)

---

## 📁 Estrutura do Projeto

API/

├── index.html #

├── main.js # 

├── package.json #

├── LICENSE # 

└── README.md # Você está aqui :)


---

## 🚀 Como Executar

> **Pré-requisitos:**  
> - Arduíno conectado via USB utilizando sensor HC-SR04
> - Certifique-se de ter o banco de dados do projeto funcionando com as credenciais corretas que chamamos no pullBancoDeDados, no arquivo main.js. O código SQL para criação do banco está disponível no repositório BANCO DE DADOS desta organização
> - Certifique-se de ter o arduino rodando através da arduíno IDE, o código está disponível no repositório ARDUINO desta organização.


1. Clone o repositório:
   ```bash
   git clone https://github.com/FitAlert/API.git
   cd API
   
2. Instale as dependências na raíz do projeto:

    ```bash
    npm install
       npm install serialport
       npm install express
       npm install mysql2

    
3. Inicie a aplicação (caso tenha um servidor local configurado):

    ```bash
    npm start
    
4. Abra o arquivo INDEX.HTML no seu navegador e verá o gráfico funcionando dinâmicamente de acordo com as entradas e saídas do arduíno.

