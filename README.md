# ESPIRAL App — portfólio técnico

[![Site de apresentação](https://img.shields.io/badge/Portf%C3%B3lio-GitHub%20Pages-b49cff?style=flat-square)](https://alan0201.github.io/espiral-portfolio/)
![Projeto de portfólio](https://img.shields.io/badge/Projeto-Estudo%20de%20caso-91edda?style=flat-square)

**Estudo de caso de desenvolvimento Full Stack do ESPIRAL App**, uma aplicação web/PWA de acompanhamento de práticas do Método ESPIRAL.

🌐 **[Acessar a apresentação](https://alan0201.github.io/espiral-portfolio/)** *(disponível após ativar o GitHub Pages nas configurações do repositório).*

> **O que este repositório é:** uma apresentação pública da experiência, arquitetura e decisões de engenharia.
>
> **O que ele não é:** não contém o código-fonte completo, os dados dos participantes, o servidor de produção nem o conteúdo protegido do método. A interface ilustrativa na página não é uma captura de tela real.

## Sobre o projeto

Aplicação responsiva desenvolvida para apoiar o uso cotidiano de práticas, registros e acompanhamentos ligados ao Método ESPIRAL. O projeto utiliza Next.js, React, TypeScript, Supabase e PostgreSQL, além de testes automatizados, controle de acesso e infraestrutura containerizada.

O **beta funcional está em preparação para um piloto fechado**; ainda não constitui evidência de uso ou impacto validado com participantes finais. O aplicativo não oferece diagnóstico, tratamento ou aconselhamento clínico.

## O que a apresentação destaca

- **Produto:** jornadas, check-ins, registros, missões, planejamento, progresso e painel administrativo;
- **Interface:** experiência mobile-first e instalação como PWA;
- **Engenharia:** arquitetura em camadas, TypeScript, validação, APIs e persistência;
- **Segurança:** autenticação, autorização no servidor e Row Level Security (RLS);
- **Qualidade:** ESLint, verificações de tipos, Vitest, Playwright e migrations;
- **Infraestrutura:** Docker e implantação em servidor Linux.

**Principais tecnologias:** Next.js · React · TypeScript · Tailwind CSS · Supabase · PostgreSQL · Docker · Vitest · Playwright.

## Como visualizar o site

Abra `index.html` diretamente no navegador. É um **site estático**, sem dependências externas, sem build e sem integração com o aplicativo restrito.

O arquivo `favicon.svg` contém o ícone e `.nojekyll` permite servir o projeto estático diretamente.

## Publicar no GitHub Pages

1. Acesse **Settings → Pages** neste repositório.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Selecione a branch **main** e a pasta **/(root)**.
4. Clique em **Save**.
5. Após o GitHub concluir a implantação, abra **https://alan0201.github.io/espiral-portfolio/**.

Não é necessário clonar o projeto privado nem fornecer credenciais para publicar esta apresentação.

## Autor

**Alan de Vicente** — graduado em Análise e Desenvolvimento de Sistemas (2026), desenvolvedor do ESPIRAL App.

- [GitHub](https://github.com/alan0201)
- [LinkedIn](https://www.linkedin.com/in/alan-vicente-3b187b116/)

## Transparência e direitos

A interface exibida no portfólio foi criada especificamente como **visualização conceitual** e não representa uma screenshot do sistema. As funcionalidades foram descritas com base na documentação técnica do projeto original. O conteúdo do Método ESPIRAL é de responsabilidade da profissional autora e não é reproduzido neste repositório.

Este portfólio não armazena dados de participantes, não usa cookies de rastreamento e não possui formulários que enviem informações.
