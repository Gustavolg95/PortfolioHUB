# 🎯 PortfolioHUB

<div align="center">
  <img src="https://img.shields.io/badge/Status-Ativo-02C39A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Versão-1.0-6B48FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge" />
</div>
<br/>
<div align="center">
  <a href="https://gustavolg95.github.io/PortfolioHUB/site/">
    <img src="https://img.shields.io/badge/🌐_Ver_Site_Online-Acessar-6B48FF?style=for-the-badge" />
  </a>
</div>
---

## 📌 O que é o PortfolioHUB?

O **PortfolioHUB** é um portfólio digital profissional centralizado, desenvolvido ao longo do  **Bootcamp I do CEUB** , com o objetivo de reunir em um único repositório toda a trajetória acadêmica, projetos, certificações e habilidades de  **Gustavo Lisboa Gonçalves** , estudante de Ciência de Dados e Machine Learning.

A plataforma integra três camadas complementares:

* 🖥️ **Google Workspace** → site, apresentação de habilidades e currículo
* 🔧 **GitHub + GitHub Pages** → versionamento do código e hospedagem pública
* 💼 **LinkedIn** → integração e visibilidade profissional

> O PortfolioHUB não é apenas um portfólio — é uma demonstração prática de boas práticas de desenvolvimento, versionamento, segurança e documentação técnica.

---

## 🎯 Objetivo

Apresentar de forma organizada e profissional:

* ✅ Habilidades técnicas em Ciência de Dados, Machine Learning e Desenvolvimento Web
* ✅ Certificações conquistadas ao longo da formação
* ✅ Projetos acadêmicos e pessoais com documentação completa
* ✅ Boas práticas de versionamento com Git e GitHub
* ✅ Políticas de segurança em repositórios públicos

---

## 🛠️ Tecnologias Utilizadas

### • Frontend

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### • Versionamento e Hospedagem

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)

### • Ferramentas Google

![Google Docs](https://img.shields.io/badge/Google_Docs-4285F4?style=flat&logo=google-docs&logoColor=white)
![Google Slides](https://img.shields.io/badge/Google_Slides-FBBC04?style=flat-square&logo=google-slides&logoColor=black)
![Google Sites](https://img.shields.io/badge/Google_Sites-4285F4?style=for-the-badge&logo=google&logoColor=white)

### • IA e Automação

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

### • Segurança

![2FA](https://img.shields.io/badge/2FA-Ativo-02C39A?style=for-the-badge&logo=authy&logoColor=white)
![.gitignore](https://img.shields.io/badge/.gitignore-Configurado-555555?style=flat-square&logo=git&logoColor=white)

---

## 📁 Estrutura do Repositório

```
PortfolioHUB/
│
├── 📄 index.html                                  → Redirecionamento para GitHub Pages
├── 📄 README.md                                   → Documentação principal (você está aqui)
├── 📄 SECURITY.md                                 → Política de segurança do repositório
├── 📄 .gitignore                                  → Proteção de arquivos sensíveis
├── 📄 PlanoImplantacao_PortfolioHUB_GustavoLisboa.docx → Plano de Implantação (Entrega Final)
│
├── 🌐 site/
│   ├── index.html             → Website do portfólio
│   └── README.md
│
├── 📋 documentos/
│   ├── Currículo Profissional.docx
│   └── README.md
│
├── 🎓 certificados/
│   ├── Certificado_Cisco_Cybersecurity.pdf
│   ├── Certificado_Git_e_GitHub.pdf
│   ├── Certificado_HTML_e_CSS_Alura.pdf
│   ├── Certificado_Imersão_Agentes_de_IA_(n8n).pdf
│   ├── Certificado_Imersão_Alura.pdf
│   ├── Certificado_ENAP.pdf
│   ├── Introduction_to_Cybersecurity_certificate_CEUB.pdf
│   └── README.md
│
├── 📊 apresentações/
│   ├── PortfolioHUB_Apresentacao.pptx
│   └── README.md
│
└── 💻 projetos/
    ├── README.md
    └── (projetos adicionados conforme desenvolvidos)
```

---

## 🚀 Como Rodar o Projeto Localmente

Siga os passos abaixo para clonar e visualizar o portfólio na sua máquina:

### Pré-requisitos

Antes de começar, você precisa ter instalado:

* [Git](https://git-scm.com/downloads) — para clonar o repositório
* Um navegador atualizado (Chrome, Edge ou Firefox)
* Opcionalmente: [VS Code](https://code.visualstudio.com/) + extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

---

### Passo 1 — Clonar o repositório

Abra o terminal (CMD, PowerShell ou Git Bash) e execute:

```bash
git clone https://github.com/Gustavolg95/PortfolioHUB.git
```

### Passo 2 — Entrar na pasta do projeto

```bash
cd PortfolioHUB
```

### Passo 3 — Abrir o site

**Opção A — Direto pelo navegador (mais simples):**

Navegue até a pasta `site/` e abra o arquivo `index.html` diretamente no navegador:

```bash
# Windows
start site/index.html

# macOS
open site/index.html

# Linux
xdg-open site/index.html
```

**Opção B — Via VS Code com Live Server (recomendado):**

```bash
# Abra a pasta no VS Code
code .
```

1. Instale a extensão **Live Server** no VS Code
2. Clique com o botão direito no arquivo `site/index.html`
3. Selecione **"Open with Live Server"**
4. O site abrirá automaticamente em `http://127.0.0.1:5500/site/index.html`

**Opção C — Acessar a versão online (sem instalação):**

```
https://gustavolg95.github.io/PortfolioHUB/site/
```

---

### Passo 4 — Explorar o repositório

```bash
# Ver a estrutura de arquivos
ls -la

# Navegar pelas pastas
cd certificados/    # Certificados digitais
cd documentos/      # Currículo
cd apresentações/   # Slides de habilidades
cd projetos/        # Projetos acadêmicos
```

---

## 🌐 Acesso Online

| Recurso               | Link                                                                                           |
| --------------------- | ---------------------------------------------------------------------------------------------- |
| 🌐 Site do Portfólio | [gustavolg95.github.io/PortfolioHUB/site/](https://gustavolg95.github.io/PortfolioHUB/site/)      |
| 💼 LinkedIn           | [Gustavo Lisboa Gonçalves](https://www.linkedin.com/in/gustavo-lisboa-gon%C3%A7alves-b103603ab/) |
| 💻 GitHub             | [@Gustavolg95](https://github.com/Gustavolg95)                                                    |

---

## 👤 Sobre o Autor

**Gustavo Lisboa Gonçalves**

* 🎓 Cursando Ciência de Dados e Machine Learning no CEUB
* 📍 Formosa, Goiás, Brasil
* 📧 lisboag.gustavo@gmail.com
* 🎸 Violonista | 💪 Academia | 🎬 Cinema | ✈️ Viajante

---

## 📜 Certificações

| Certificação                       | Instituição            | Data     |
| ------------------------------------ | ------------------------ | -------- |
| Imersão Agentes de IA com n8n       | Hashtag Treinamentos     | Fev/2026 |
| Introduction to Cybersecurity        | Cisco Networking Academy | Mar/2026 |
| Introdução à Cibersegurança      | CEUB via Cisco           | Mar/2026 |
| Git + GitHub Essencial para Dados    | Udemy                    | Mar/2026 |
| HTML e CSS: Praticando HTML/CSS      | Alura                    | Abr/2026 |
| Imersão Front-End com IA            | Alura                    | Abr/2026 |
| IA Além do Chat — Gestão Pública | ENAP                     | Mai/2026 |

---

## 🔒 Segurança

Este repositório adota as seguintes práticas de segurança:

* ✅ Autenticação em dois fatores (2FA) ativada na conta GitHub
* ✅ Arquivo `.gitignore` configurado para proteger dados sensíveis
* ✅ Nenhum token, senha ou chave de API no código
* ✅ Política de segurança documentada em [`SECURITY.md`](https://claude.ai/chat/SECURITY.md)
* ✅ Dependabot Alerts habilitado

---

## 🤖 Apoio de IA

Este projeto foi desenvolvido com apoio do **Gemini (Google)** como ferramenta de IA assistente:

* Planejamento da estrutura do repositório
* Geração e revisão do código HTML/CSS/JS
* Criação da documentação técnica
* Implementação de boas práticas de segurança
* Elaboração do Plano de Implantação (Bootcamp I — Entrega Final)

> **Referência:** Gemini, desenvolvido pelo Google. Modelo: Flash 3.5. Disponível em: [gemini.google.com](https://gemini.google.com/). Acesso em: Junho de 2026.

---

## 🎯 Objetivo Profissional

Busco minha primeira oportunidade profissional na área de  **Ciência de Dados** , **Machine Learning** ou  **Desenvolvimento de Software** , onde possa aplicar conhecimentos técnicos em projetos reais e contribuir com soluções inovadoras.

---

<div align="center">

**Desenvolvido com 💙 por Gustavo Lisboa Gonçalves**

*Bootcamp I — CEUB 2026*

[![GitHub](https://img.shields.io/badge/GitHub-Gustavolg95-181717?style=flat-square&logo=github)](https://github.com/Gustavolg95)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gustavo_Lisboa-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/gustavo-lisboa-gon%C3%A7alves-b103603ab/)
[![Email](https://img.shields.io/badge/Email-lisboag.gustavo@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:lisboag.gustavo@gmail.com)

</div>

---

*Última atualização: Maio/Junho de 2026*
