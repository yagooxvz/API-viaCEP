# 📍 API ViaCEP — Consulta de CEP em Java

> Aplicação desenvolvida em **Java** para consulta de CEP através da **API ViaCEP**, com processamento de dados em JSON e geração de um arquivo com o resultado da consulta.

---

## Sobre o projeto

A aplicação permite que o usuário informe um **CEP pelo terminal**. A partir desse CEP, o programa realiza uma requisição à **API ViaCEP** e recebe os dados do endereço em formato JSON.

As informações retornadas são processadas e apresentadas no terminal:

*  CEP
*  Logradouro
*  Complemento
*  Bairro
*  Localidade
*  UF

Após a consulta, a aplicação também gera um arquivo `.json` contendo os dados obtidos.

---

## ⚙️ Como funciona

```text
👤 Usuário informa o CEP
          ↓
🌐 Requisição HTTP
          ↓
📡 API ViaCEP
          ↓
📄 Resposta em JSON
          ↓
☕ Gson → Objeto Java
          ↓
💻 Exibição no terminal
          ↓
📄 Geração do arquivo JSON
```

---

## 🛠️ Tecnologias utilizadas

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge\&logo=openjdk)
![Maven](https://img.shields.io/badge/Maven-Build%20Tool-C71A36?style=for-the-badge\&logo=apachemaven)
![Gson](https://img.shields.io/badge/Gson-JSON-4285F4?style=for-the-badge\&logo=google)
![Git](https://img.shields.io/badge/Git-Versionamento-F05032?style=for-the-badge\&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?style=for-the-badge\&logo=github)

### Conceitos praticados

* ☕ Java 17
* 🌐 Consumo de API REST
* 🔄 Requisições HTTP
* 📄 Manipulação e conversão de JSON
* 📦 Biblioteca Gson
* 🔨 Maven
* 💻 Entrada de dados pelo terminal
* 📁 Geração de arquivos JSON
* 🔀 Git e GitHub

---

## 🎯 Objetivo

O projeto foi desenvolvido como prática de conceitos importantes para o desenvolvimento **back-end com Java**, principalmente a comunicação com serviços externos, consumo de APIs, processamento de dados e integração com bibliotecas.

---

## 👨‍💻 Autor

**Yago Souza**

Desenvolvedor Full-Stack | JavaScript | React | TypeScript | Java | Spring Boot

[![GitHub](https://img.shields.io/badge/GitHub-yagooxvz-181717?style=for-the-badge\&logo=github)](https://github.com/yagooxvz)

---
