# Projeto CI/CD com Azure App Service e GitHub Actions

Este projeto demonstra a criação de uma aplicação web simples publicada no **Azure App Service**, com deploy automatizado por meio do **GitHub Actions**.

## Objetivo

Implementar um pipeline CI/CD para automatizar o processo de publicação de uma página HTML no Azure App Service.

## Tecnologias utilizadas

- HTML
- GitHub
- GitHub Actions
- Azure App Service
- Azure Monitor
- GitHub Secrets

## Vantagens do CI/CD

CI/CD permite automatizar etapas de integração e entrega de software, reduzindo erros humanos, acelerando o deploy de novas versões e aumentando a confiabilidade da aplicação em produção.

## Estrutura do projeto

```text
.
├── index.html
├── README.md
└── .github
    └── workflows
        └── deploy.yml
