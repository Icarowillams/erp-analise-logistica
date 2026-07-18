<h1 align="center">🏭 Sistema ANÁLISE + LOGÍSTICA</h1>

<p align="center">
  <b>ERP de gestão comercial e logística integrado ao Omie</b><br/>
  Desenvolvido individualmente, do zero, e utilizado em produção.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Produção-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tipo-SFA%20%2F%20TMS-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Integração-ERP%20Omie-orange?style=for-the-badge"/>
</p>

---

## 📌 Sobre o Projeto

Sistema completo de **força de vendas (SFA)** e **gestão logística (TMS)** construído para uma indústria de panificação, substituindo o sistema legado da empresa.

Atuei como **único profissional de TI**, responsável por todas as camadas — do levantamento de requisitos à arquitetura, backend, frontend, integração com ERP, deploy e sustentação em produção.

O sistema é usado **diariamente** pelos setores comercial, logística, produção e faturamento, sustentando o fluxo completo: do pedido em campo até a entrega, a nota fiscal e o boleto.

---

## 📊 Números do Projeto

| Métrica | Valor |
|---|---|
| ⚡ Funções backend | **97** |
| 🖥️ Telas | **53** |
| 🧩 Componentes React | **235** |
| 🗃️ Entidades de dados | **69** |
| 👥 Usuários ativos | **20+** |
| 🧑‍💼 Vendedores | **81** |
| 🏪 Clientes | **1.157** |

---

## 🏗️ Arquitetura & Destaques Técnicos

- 🔌 **Integração em tempo real com o ERP Omie** via Webhooks e filas assíncronas
- 🧾 **Automação fiscal**: emissão de NF-e em lote integrada à SEFAZ, com validação prévia, acompanhamento de retorno (autorizada/rejeitada/cancelada) e reconciliação automática de DANFEs e boletos
- 🛡️ **Fundação anti-bloqueio de API (4 camadas)**: Circuit Breaker com half-open, rate limiting global atômico, coalescing de requisições e orçamento de erros por método — garantindo que a operação **nunca pare**
- ♻️ **Idempotência e prevenção de duplicatas** em pedidos, notas fiscais e clientes
- 📈 **Dashboards em tempo real** de vendas, trocas, comissão e desempenho de vendedores
- 🗺️ **Gestão de rotas e cargas** com montagem de roteiros por vendedor e dia

---

## 🛠️ Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-000000?style=for-the-badge&logo=deno&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Integração:** API Omie (SOAP/REST) · Webhooks · NF-e / SEFAZ · ViaCEP

---

## 📄 Documentação

📥 **[Portfólio Técnico Completo (PDF)](./Portfolio_Comercial_Logistica.pdf)** — arquitetura detalhada, decisões técnicas e impacto de negócio.

---

<p align="center">
  <i>⚠️ O código-fonte é privado por se tratar de sistema proprietário em produção.<br/>
  Este repositório é uma vitrine técnica do projeto.</i>
</p>

<p align="center">
  <b>Ícaro Willams</b> — Desenvolvedor Full Stack<br/>
  <a href="https://linkedin.com/in/icaro-ramoss">LinkedIn</a> ·
  <a href="mailto:icarowilllams17@gmail.com">Email</a>
</p>
