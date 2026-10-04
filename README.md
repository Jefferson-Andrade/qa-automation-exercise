# QA Portfolio | Automation Exercise - Teste Manual

![QA](https://img.shields.io/badge/QA-Manual_Testing-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Cobertura da matriz](https://img.shields.io/badge/Requisitos_vinculados_na_matriz-24%2F24-blue)
![Test Cases](https://img.shields.io/badge/Test%20Cases-42-informational)
![Requirements](https://img.shields.io/badge/Requisitos_na_matriz-24-orange)

## 📖 Sobre o Projeto

Este repositório contém um projeto completo de **Engenharia de Testes** desenvolvido como portfólio para área de **Quality Assurance (QA)**.

O objetivo foi validar funcionalmente o sistema [**Automation Exercise**](https://automationexercise.com/), simulando o fluxo de trabalho adotado em equipes de QA, desde o levantamento de requisitos até a execução dos testes e elaboração da documentação final.

Todo o projeto foi desenvolvido seguindo boas práticas de documentação inspiradas na **IEEE 29148 (Software Requirements Specification)** e nos processos tradicionais de testes de software.

---

## Escopo da cobertura

O projeto realizou testes funcionais manuais de caixa-preta na interface web do [Automation Exercise](https://automationexercise.com/). O ciclo documentado contém **42 casos de teste (CT001–CT042)**, associados aos **24 requisitos cadastrados na matriz de rastreabilidade (RF001–RF024)**.

### Funcionalidades avaliadas

| Área | Cenários documentados | Casos de teste |
|---|---|---|
| Cadastro | Cadastro válido, e-mail existente, nome/e-mail ausentes, e-mail inválido e interrupção do cadastro | CT001–CT006 |
| Login, logout e conta | Credenciais válidas, senha incorreta, e-mail não cadastrado, campos vazios, logout e exclusão de conta | CT007–CT011, CT042 |
| Produtos | Listagem, detalhes, busca com e sem resultados, categorias, marcas e troca de categorias | CT012–CT018 |
| Carrinho | Adição de um ou vários produtos, visualização, remoção, carrinho vazio e manutenção dos itens durante a navegação | CT019–CT025 |
| Checkout e pagamento | Entrada com/sem autenticação, conferência do pedido, dados de pagamento válidos, campos obrigatórios vazios e confirmação | CT026–CT031 |
| Contato | Envio válido, campos obrigatórios vazios e envio com anexo | CT032–CT034 |
| Newsletter | Inscrição com e-mail válido e tentativa sem e-mail | CT035–CT036 |
| Avaliações | Envio válido e tentativa sem campos obrigatórios | CT037–CT038 |
| Navegação | Acesso às páginas principais, retorno pelo menu Home e botão Scroll Up | CT039–CT041 |

Os casos incluem fluxos positivos, negativos e um fluxo alternativo. O escopo exato, os dados, os passos e os resultados esperados estão na [planilha de casos de teste](docs/Casos_de_Teste_Automation_Exercise.xlsx). A classificação de prioridade de cada caso está registrada nessa planilha.

### Ambiente e limites

O [relatório final](docs/%5BGURU%5D%20Relat%C3%B3rio%20Final%20de%20Testes.docx) registra execução no ambiente web público, com **Google Chrome em Linux**, e evidências em PNG. Não informa a versão exata do navegador nem a resolução utilizada. A execução não representa validação de todas as combinações de navegadores, sistemas e dispositivos.

O pagamento foi avaliado como fluxo da aplicação de demonstração, sem processamento financeiro real. A confirmação de contato, inscrição e avaliação pela interface não comprova entrega de e-mail ou funcionamento de serviços externos.

Conforme o plano de testes, ficaram fora do escopo:

- Automação, testes diretos de API, testes unitários e testes de integração.
- Desempenho, carga, stress e segurança.
- Acessibilidade e compatibilidade entre diversos navegadores e dispositivos.
- Instalação, recuperação de desastres e tolerância a falhas.

Os [cenários oficiais do site](https://automationexercise.com/test_cases) servem como referência para possíveis ampliações. Os 42 casos deste projeto possuem organização própria; não há um mapeamento documentado que comprove a execução de todos os 26 cenários oficiais.

### Como interpretar a cobertura

- **Cobertura de requisitos na matriz:** 24 de 24 itens possuem casos associados, equivalente a 100% dessa matriz.
- **Execução registrada:** 42 de 42 casos estão marcados como “Passou” na planilha.
- **Limite da conclusão:** esses percentuais não representam cobertura de código, de todas as funcionalidades do site ou de todos os ambientes. Nenhum bug registrado nesse ciclo não significa ausência de defeitos no sistema.

**Pendência de consistência documental:** a ERS descreve 27 requisitos (RF01–RF27), enquanto a matriz e a planilha de casos utilizam 24 (RF001–RF024), com diferenças de descrição além da formatação dos IDs. Por exemplo, RF14 na ERS trata de remoção do carrinho, enquanto RF014 na matriz trata de visualização. Portanto, a cobertura de 100% de toda a ERS ainda depende da revisão desse mapeamento. Os resultados acima preservam os registros existentes, sem contar requisitos adicionais como validados.

### Rastreabilidade e conclusão do ciclo

O plano estabelece como critérios de saída a execução dos casos previstos, o registro de evidências e defeitos, a atualização da matriz e a emissão do relatório final. O resultado do ciclo deve ser consultado nos artefatos; a revisão da correspondência entre ERS, casos e matriz é uma pendência documental.

Uma captura de tela apoia a evidência de uma execução, mas não comprova isoladamente todos os passos e resultados de um caso.

---

## Objetivos

* Levantar e documentar requisitos funcionais.
* Elaborar um Plano de Testes.
* Projetar Casos de Teste.
* Construir uma Matriz de Rastreabilidade.
* Executar todos os testes manuais.
* Registrar evidências da execução.
* Organizar o fluxo de trabalho utilizando Jira.
* Elaborar um Relatório Final de Testes.

---

## Ferramentas Utilizadas

| Ferramenta          | Finalidade                       |
| ------------------- | -------------------------------- |
| Microsoft Excel     | Casos de Teste                   |
| Microsoft Word      | Documentação                     |
| Jira Software       | Gerenciamento das atividades     |
| Automation Exercise | Sistema sob teste                |
| GitHub              | Versionamento e Portfólio        |

---

## Documentação Produzida

O projeto contempla toda a documentação a seguir:

| Documento                         | Status |
| --------------------------------- | :----: |
| [Especificação de Requisitos (ERS)](docs/%5BGURU%5D%20Especifica%C3%A7%C3%A3o%20de%20Requisitos%20.docx) | ✅ |
| [Plano de Testes](docs/%5BGURU%5D%20Plano%20de%20Testes.docx) | ✅ |
| [Casos de Teste](docs/Casos_de_Teste_Automation_Exercise.xlsx) | ✅ |
| [Matriz de Rastreabilidade](docs/Matriz_de_Rastreabilidade.xlsx) | ✅ |
| [Registro da Execução (coluna Status dos casos)](docs/Casos_de_Teste_Automation_Exercise.xlsx) | ✅ |
| [Evidências](evidencias/) | ✅ |
| [Relatório Final](docs/%5BGURU%5D%20Relat%C3%B3rio%20Final%20de%20Testes.docx) | ✅ |

---

## Métricas do Projeto

Resultados registrados na planilha de casos de teste e no relatório final. O percentual de requisitos refere-se à matriz de 24 itens; a divergência com a ERS está detalhada no escopo acima.

| Indicador             | Resultado |
| --------------------- | --------: |
| Requisitos na matriz  |    **24** |
| Casos de Teste        |    **42** |
| Casos Executados      |    **42** |
| Casos Aprovados       |    **42** |
| Casos Reprovados      |     **0** |
| Casos Bloqueados      |     **0** |
| Requisitos vinculados na matriz | **24/24 (100%)** |
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

## Estrutura do Repositório

```text
.
├── docs
│   ├── Casos_de_Teste_Automation_Exercise.xlsx
│   ├── [GURU] Especificação de Requisitos .docx
│   ├── [GURU] Plano de Testes.docx
│   ├── [GURU] Relatório Final de Testes.docx
│   ├── Matriz_de_Rastreabilidade.xlsx
│   └── Matriz_de_Rastreabilidade.ods
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

## Fluxo de Testes

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

## Evidências

As capturas estão organizadas por módulo em [evidencias/](evidencias/) e identificadas pelo código do caso. Para CT041, o arquivo existente chama-se `evidencias/navegacao/CT0041.png`.

A rastreabilidade deve relacionar:

* Requisito
* Caso de Teste
* Execução
* Evidência

---

## Gerenciamento das Atividades

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

## Resultado Final

A planilha registra os 42 casos como aprovados, e o relatório final informa que nenhum bug foi identificado durante esse ciclo. A correspondência integral com a ERS depende da revisão documental descrita no escopo.

A execução contemplou:

* 24 requisitos cadastrados na matriz
* 42 casos de teste registrados como executados e aprovados
* 100% dos itens da matriz com casos associados
* Nenhum bug registrado no relatório final
* Artefatos de planejamento, execução e consolidação disponíveis no repositório

---

## Possíveis Evoluções

A primeira evolução documental é alinhar os identificadores e descrições da ERS, da matriz e dos casos, e recalcular a cobertura sobre o conjunto reconciliado.

Como continuidade deste projeto, podem ser implementadas novas etapas, como:

* Automatização dos casos de teste com Selenium
* Testes automatizados com Cypress
* Testes de API utilizando Postman
* Testes de Performance com JMeter
* Integração contínua (CI/CD) utilizando GitHub Actions
* Geração automatizada de relatórios de execução

---

⭐ Caso este projeto tenha sido útil ou interessante, deixe uma estrela no repositório.
