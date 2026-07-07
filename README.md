# Anamnesis E-commerce Platform

Plataforma de e-commerce fullstack para venda de documentos digitais, com fluxo de anamnese pré-compra para validação de dados do cliente, checkout integrado e painel administrativo completo.

![Stack](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Stack](https://img.shields.io/badge/Nest.js-E0234E?style=flat&logo=nestjs&logoColor=white)
![Stack](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Stack](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Stack](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Stack](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Stack](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

## 📸 Imagens do projeto

<!-- Troque os nomes abaixo pelos arquivos reais da pasta assets/ -->

**Página inicial / vitrine de produtos**
![Home](./assets/home.png)

**Fluxo de anamnese (validação pré-compra)**
![Anamnese](./assets/anamnese-flow.png)

**Checkout — Pagar.me (Pix e cartão)**
![Checkout](./assets/checkout.png)

**Painel administrativo — gestão de produtos**
![Admin](./assets/ficha/admin/1.png)
![Admin](./assets/ficha/admin/2.png)
![Admin](./assets/ficha/admin/3.png)
![Admin](./assets/ficha/admin/4.png)
![Admin](./assets/ficha/admin/5.png)
![Admin](./assets/ficha/admin/6.png)

## 🧩 Sobre o projeto

Sistema desenvolvido para automatizar a venda de documentos digitais, com foco em segurança de dados, validação de informações do cliente antes da compra (anamnese) e automação de processos financeiros. Projeto em produção, desenvolvido de ponta a ponta (API, painel admin e infraestrutura).

## ⚙️ Funcionalidades

- Catálogo de produtos digitais com cadastro via painel admin
- Fluxo de anamnese para validação de dados antes da finalização da compra
- Checkout com Pagar.me — Pix e cartão de crédito
- Upload e armazenamento seguro de documentos e imagens via AWS
- Painel administrativo em Next.js para gestão de produtos e pedidos
- API REST em Nest.js com Prisma ORM e PostgreSQL

## 🛠️ Tecnologias

| Camada | Tecnologias |
|---|---|
| Backend | Nest.js, Prisma ORM, PostgreSQL |
| Frontend / Admin | Next.js, React |
| Pagamentos | Pagar.me (Pix, Cartão de Crédito) |
| Armazenamento | AWS |
| Infraestrutura | Docker, VPS Linux, Nginx, Fail2ban |

## 🚀 Deploy

Aplicação em produção, com deploy em VPS própria (Docker + Nginx) e proteção contra acessos indevidos via Fail2ban.

---

Desenvolvido por [Tiago Ramon Becker](https://github.com/TiagoRBecker) — [Portfólio](https://tiagobecker.vercel.app/)
