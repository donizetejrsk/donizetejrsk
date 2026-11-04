# Donizete Junior

Sou desenvolvedor, no Brasil, e escrevo JavaScript e Java. Passo a maior parte do tempo ligando coisas ao ERP Sankhya: telas, extensões, importações, relatórios e rotinas agendadas. Em cima dessas integrações construí uns produtos pequenos, que juntei sob o nome Sanktor.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_SQL-F80000?style=flat&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

## No que eu trabalho

Extensões e telas para o Sankhya. Uso Java para ações agendadas, eventos e botões de ação, e HTML5, JSP e JavaScript para as telas dentro do ERP. Quando uma tela cresce demais, migro para React, Vite e TypeScript e publico o bundle por um CDN próprio, sem mexer no que o cliente já tem instalado.

Integrações. Já liguei o ERP a Cielo, Correios, Tray, DataFrete e Mercado Livre, e já gerei arquivos de PIX, de retorno bancário e de contabilidade. Boa parte desse trabalho é conciliar o dado de um lado com o do outro e descobrir por que não bate.

Atendimento e WhatsApp. Campanhas com controle de bloqueio, notificações automáticas e um helpdesk que conversa com o cliente pelo WhatsApp.

Ferramentas para IA. Escrevi servidores MCP para o Claude e o Codex consultarem o Sankhya e o helpdesk. Eles abrem em modo leitura, e escrever no ERP exige ligar isso de propósito.

## Sanktor

Os repositórios são privados. O que existe hoje:

- Sanktor Hub: helpdesk, CRM, agenda, workflow, cobrança e um CDN de scripts para publicar telas no Sankhya.
- Sanktor Alcance: campanhas por WhatsApp.
- Sanktor Caixa: adiantamentos e prestação de contas, com leitura de comprovantes por OCR.
- Sanktor Force: pedidos, crediário e pagamento por Pix e cartão.
- Sanktor Finance: painel financeiro que roda como tela dentro do Sankhya.

Site: [sanktor.com.br](https://sanktor.com.br)

## Como eu trabalho

Gosto de começar pelo dado real. Reproduzo o problema no banco do cliente antes de escrever uma linha. Quando migro uma tela, rodo a antiga e a nova com o mesmo conjunto de dados e comparo relatório, textos e o que seria gravado no ERP. Só entrego se for idêntico.

Uso Claude Code e Codex como par de programação. Eles escrevem rápido, e eu leio tudo que eles escrevem.

## Ferramentas do dia a dia

Linguagens: JavaScript, TypeScript, Java, SQL (Oracle).

Front: React, Vite, Tailwind, HTML5.

Back: Node.js, Express, Docker Compose, Traefik.

Qualidade: Playwright, testes de regressão contra a versão anterior.

Versionamento: Git, GitHub e GitLab.
