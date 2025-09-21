# Greeting Service 🚀

Um microserviço simples desenvolvido em **Java + Spring Boot** que retorna uma saudação via endpoint REST.  
Este projeto é utilizado como exemplo para estudar **microserviços, containers (Docker) e orquestração futura com Kubernetes**.

---

## 📂 Estrutura do Projeto

```plaintext

greeting-service/
├── src/
│ └── main/
│ ├── java/com/example/greeting/GreetingServiceApplication.java
│ └── resources/application.properties
├── Dockerfile
├── pom.xml
└── README.md

```

---

## ⚙️ Tecnologias utilizadas
- **Java 21**
- **Spring Boot 3**
- **Maven**
- **Docker**

---

## ▶️ Executando localmente

Clone o repositório e compile o projeto com Maven:

```bash
git clone https://github.com/seu-usuario/greeting-service2.git
cd greeting-service2
mvn spring-boot:run

```

O serviço ficará disponível em:\
👉 http://localhost:8080/greeting

## 🐳 Executando com Docker

### 1. Build da imagem

```bash

docker build -t greeting-service2 .

```



