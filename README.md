# 🩺 Desafio Técnico QA: Lacrei Saúde - Análise e Planejamento

Este repositório contém o planejamento e a documentação dos testes de Qualidade de Software realizados na aplicação Lacrei Saúde (ambiente Staging), conforme o escopo do Desafio Técnico.

---

## 🚨 STATUS CRÍTICO DA APLICAÇÃO

O fluxo de teste principal está **BLOQUEADO** devido a uma falha de alta severidade na API de Login.

* **Problema:** Falha 403 Forbidden ao tentar realizar o Login.
* **Referência:** [Registro de Bug - 001](https://www.notion.so/Registro-de-Bug-001-2a390b9e5c4d80e38c0ac943c34c2554?source=copy_link)
https://www.notion.so/Readme-e-Links-Github-relatorios-prints-1-2a390b9e5c4d807f9974dc2ec30590df?source=copy_link
---

## 🔗 DOCUMENTAÇÃO COMPLETA (Notion)

Todo o detalhamento dos testes, evidências e relatórios está centralizado no Notion:

| Documento | Link de Acesso |
| :--- | :--- |
| **Relatório Execução Final (Tabela)** | [Execução de testes (Mobile)](https://www.notion.so/Execu-ao-de-testes-Mobile-6-2a390b9e5c4d806a85d2c185fe45c6aa?source=copy_link) |
| **Relatório Executivo (Este README)** | [Readme e Links (Notion)](https://www.notion.so/Readme-e-Links-Github-relatorios-prints-2a390b9e5c4d807f9974dc2ec30590df?source=copy_link) |
| **Planejamento de Testes Gherkin** | [Casos de teste (Gherkin)](https://www.notion.so/Casos-de-teste-1-Gherkin-2a390b9e5c4d801c8fdccf2a79b86df9?source=copy_link) |


### 4. PLANEJAMENTO ESTRUTURAL (AUTOMAÇÃO - Entregável 7)

A estratégia de automação foi desenhada para garantir a cobertura End-to-End (E2E) dos fluxos críticos, utilizando as ferramentas mais adequadas para o ambiente web.

* **Framework Escolhido:** **Cypress**
* **Linguagem/Ferramentas:** **JavaScript**, **Node.js** e **NPM** (para gerenciamento de pacotes).

#### Evidência de Configuração

A automação foi estruturada no VS Code, onde o **Node.js** e o **NPM** foram utilizados para instalar o **Cypress** (`npm install cypress`). O código do projeto (no repositório) já possui a estrutura de pastas e o arquivo `package.json` configurados para rodar os testes.

**Status:** A implementação dos testes E2E está **BLOQUEADA** e será priorizada após a correção do BUG-001.

---

### 5. PLANEJAMENTO DE TESTES FUNCIONAIS

Embora bloqueados, os casos de teste funcionais para a aplicação foram planejados em Gherkin.

* **Foco:** Testes de Busca de Profissional e Edição de Perfil.
* **Documentação:** [Casos de teste (Gherkin)](https://www.notion.so/Casos-de-teste-1-Gherkin-2a390b9e5c4d801c8fdccf2a79b86df9?source=copy_link)
<img width="993" height="747" alt="image" src="https://github.com/user-attachments/assets/39c5eb56-2695-4f6e-a764-8f5c66d0b5cf" />


Conclusão e documentação do Desafio Técnico QA Lacrei Saúde, incluindo o planejamento de automação (Cypress/Node), relatórios de Acessibilidade (Score 96) e Performance (LCP crítico), e o registro de três bugs de alta severidade (como o 403 Forbidden no Login). [[Link para o meu Notion completo](https://www.notion.so/2a390b9e5c4d80ffbab8c43cc08641b7?v=2a390b9e5c4d80f8b09a000cd484059c&source=copy_link)]
