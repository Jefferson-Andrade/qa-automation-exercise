# QA Portfolio | Automation Exercise - Teste Manual

![QA](https://img.shields.io/badge/QA-Manual_Testing-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Coverage](https://img.shields.io/badge/Coverage-100%25-brightgreen)
![Test Cases](https://img.shields.io/badge/Test%20Cases-42-informational)
![Requirements](https://img.shields.io/badge/Requirements-24-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📖 Sobre o Projeto

Este repositório contém um projeto completo de **Engenharia de Testes** desenvolvido como portfólio para área de **Quality Assurance (QA)**.

O objetivo foi validar funcionalmente o sistema [**Automation Exercise**](https://automationexercise.com/), simulando o fluxo de trabalho adotado em equipes de QA, desde o levantamento de requisitos até a execução dos testes e elaboração da documentação final.

Todo o projeto foi desenvolvido seguindo boas práticas de documentação inspiradas na **IEEE 29148 (Software Requirements Specification)** e nos processos tradicionais de testes de software.

---

# Objetivos

* Levantar e documentar requisitos funcionais.
* Elaborar um Plano de Testes.
* Projetar Casos de Teste.
* Construir uma Matriz de Rastreabilidade.
* Executar todos os testes manuais.
* Registrar evidências da execução.
* Organizar o fluxo de trabalho utilizando Jira.
* Elaborar um Relatório Final de Testes.

---

# Ferramentas Utilizadas

| Ferramenta          | Finalidade                       |
| ------------------- | -------------------------------- |
| Microsoft Excel     | Casos de Teste                   |
| Microsoft Word      | Documentação                     |
| Jira Software       | Gerenciamento das atividades     |
| Automation Exercise | Sistema sob teste                |
| GitHub              | Versionamento e Portfólio        |

---

# Documentação Produzida

O projeto contempla toda a documentação a seguir:

| Documento                         | Status |
| --------------------------------- | :----: |
| Especificação de Requisitos (ERS) |    ✅   |
| Plano de Testes                   |    ✅   |
| Casos de Teste                    |    ✅   |
| Matriz de Rastreabilidade         |    ✅   |
| Registro da Execução              |    ✅   |
| Evidências                        |    ✅   |
| Relatório Final                   |    ✅   |

---

# Métricas do Projeto

| Indicador             | Resultado |
| --------------------- | --------: |
| Requisitos Funcionais |    **24** |
| Casos de Teste        |    **42** |
| Casos Executados      |    **42** |
| Casos Aprovados       |    **42** |
| Casos Reprovados      |     **0** |
| Casos Bloqueados      |     **0** |
| Cobertura Funcional   |  **100%** |
| Bugs Encontrados      |     **0** |


## Cobertura por Módulo

| Módulo         | Casos |
| -------------- | ----: |
| Cadastro       |     6 |
| Login / Logout |     6 |
| Produtos       |     7 |
| Carrinho       |     7 |
| Checkout       |     6 |
| Contato        |     3 |
| Newsletter     |     2 |
| Avaliações     |     2 |
| Navegação      |     3 |

Total de Casos de Teste: **42**

---

# Estrutura do Repositório

```text
.
├── docs
│   ├── Casos_de_Teste_Automation_Exercise.xlsx
│   ├── Especificação de Requisitos.docx
│   ├── Plano de Testes.docx
│   ├── Relatório Final de Testes.docx
│   └── Matriz_de_Rastreabilidade.xlsx
│
├── evidencias
│   ├── cadastro
│   ├── login
│   ├── produtos
│   ├── carrinho
│   ├── checkout
│   ├── contato
│   ├── newsletter
│   ├── avaliacoes
│   └── navegacao
│
├── jira
│   ├── jira_backlog.png
│   ├── jira_kanban.png
│   └── jira_task.png
│
└── README.md
```

---

# Fluxo de Testes

```text
Levantamento de Requisitos
            │
            ▼
Especificação de Requisitos (ERS)
            │
            ▼
Plano de Testes
            │
            ▼
Casos de Teste
            │
            ▼
Matriz de Rastreabilidade
            │
            ▼
Execução dos Testes
            │
            ▼
Coleta de Evidências
            │
            ▼
Relatório Final
```

---

# Evidências

Todas as evidências foram organizadas por módulo. Cada captura de tela corresponde diretamente ao seu respectivo Caso de Teste (CT001–CT042), permitindo total rastreabilidade entre:

* Requisito
* Caso de Teste
* Execução
* Evidência

---

# Gerenciamento das Atividades

O planejamento e a execução das atividades foram organizados utilizando o **Jira Software**.

As capturas da ferramenta encontram-se disponíveis em:

```
jira/
```

Incluindo:

* Backlog
* Quadro Kanban
* Task de execução dos testes

---

# Resultado Final

Todos os requisitos definidos na Especificação de Requisitos foram validados com sucesso.

A execução contemplou:

* 24 requisitos funcionais
* 42 casos de teste
* Cobertura funcional de 100%
* Nenhum bug identificado durante a execução
* Documentação completa do processo de QA

---

# Possíveis Evoluções

Como continuidade deste projeto, podem ser implementadas novas etapas, como:

* Automatização dos casos de teste com Selenium
* Testes automatizados com Cypress
* Testes de API utilizando Postman
* Testes de Performance com JMeter
* Integração contínua (CI/CD) utilizando GitHub Actions
* Geração automatizada de relatórios de execução

---

⭐ Caso este projeto tenha sido útil ou interessante, deixe uma estrela no repositório.
