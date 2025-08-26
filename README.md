# Servidor Apache com Docker Compose 🚀

Este projeto cria um servidor **Apache (httpd)** rodando em um container Docker, servindo uma aplicação simples "Hello World".

## 📂 Estrutura do Projeto
- **docker-compose.yml** → Define o serviço Apache.  
- **app/index.html** → Página simples de exemplo "Hello World".  

## ▶️ Como executar

1. Clone este repositório:
   git clone https://github.com/seu-usuario/meu-apache.git
   cd meu-apache

2. Suba o container com Docker Compose:
   docker-compose up -d

3. Acesse no navegador:
   http://localhost:8080

Você verá a página **Hello World! 🚀**

## 🛠️ Tecnologias utilizadas
- Docker
- Apache HTTP Server (httpd)
