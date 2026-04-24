# 🌐 AWS Cloud Portfolio (S3 + CloudFront)

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![CloudFront](https://img.shields.io/badge/Amazon-CloudFront-blue)
![S3](https://img.shields.io/badge/Amazon-S3-orange)
![HTTPS](https://img.shields.io/badge/HTTPS-SSL-green)

![Project Preview](preview.png)

Projeto de portfólio pessoal publicado em produção na AWS, com foco em Cloud Computing, segurança e distribuição global de conteúdo.

---

## 🔗 Live Demo

https://www.raphaely.dev

---

## 🧠 Sobre o projeto

Este projeto demonstra a implementação de uma arquitetura de hospedagem estática segura na AWS, utilizando serviços como Amazon S3, CloudFront e Certificate Manager.

O objetivo foi simular um ambiente de produção, garantindo:

- distribuição global de conteúdo
- comunicação segura via HTTPS
- controle de acesso ao armazenamento

---

## ☁️ Arquitetura

Internet → CloudFront (HTTPS) → Origin Access Control (OAC) → S3 (privado)

### 📊 Diagrama da Arquitetura

![AWS Architecture](aws-architecture.png)

---

## 🛠️ Tecnologias utilizadas

### Cloud & Infraestrutura
- Amazon S3 (bucket privado)
- Amazon CloudFront (CDN global)
- Origin Access Control (OAC)
- AWS Certificate Manager (SSL/HTTPS)
- Domínio personalizado (raphaely.dev)
- DNS

### Ferramentas
- Git e GitHub
- Linux
- SSH

### Interface
- HTML e CSS
- Desenvolvimento assistido por IA

---

## ⚙️ Etapas do projeto

1. Criação do bucket no Amazon S3  
2. Configuração do bucket como origem privada  
3. Criação da distribuição no CloudFront  
4. Configuração do Origin Access Control (OAC)  
5. Provisionamento de certificado SSL via AWS Certificate Manager  
6. Integração com domínio personalizado  
7. Publicação do site com HTTPS ativo  

---

## 🎯 Objetivo

Demonstrar na prática a implementação de uma arquitetura de hospedagem estática segura na AWS, utilizando CDN, HTTPS e controle de acesso ao armazenamento.

---

## 📌 Observações

A infraestrutura foi configurada manualmente na AWS com o objetivo de aprofundar o entendimento dos serviços e da arquitetura.

---

## 👨‍💻 Autor

Raphaely Magalhães

- LinkedIn: https://linkedin.com/in/raphaely-magalhaes
- GitHub: https://github.com/raphaelymc