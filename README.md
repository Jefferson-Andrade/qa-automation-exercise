# QA Manual | Automation Exercise

Projeto de portfólio de testes funcionais manuais do [Automation Exercise](https://automationexercise.com/), com planejamento, casos de teste, matriz de rastreabilidade, evidências e relatório final.

O ciclo documentado registra **42 casos executados e aprovados**, distribuídos em nove módulos. A matriz possui **24 requisitos com casos associados**. Existe uma pendência de correspondência com os **27 requisitos da ERS**, detalhada adiante.

## Como explorar o projeto

| Etapa | Artefato | O que consultar |
| --- | --- | --- |
| 1. Entender o sistema | [Especificação de Requisitos (ERS)](docs/%5BGURU%5D%20Especifica%C3%A7%C3%A3o%20de%20Requisitos%20.docx) | Regras de negócio, requisitos e restrições |
| 2. Conhecer a estratégia | [Plano de Testes](docs/%5BGURU%5D%20Plano%20de%20Testes.docx) | Escopo, técnicas propostas, critérios e riscos |
| 3. Examinar os testes | [Casos de Teste](docs/Casos_de_Teste_Automation_Exercise.xlsx) | Pré-condições, passos, dados, resultados esperados, prioridade e status |
| 4. Conferir os vínculos | [Matriz de Rastreabilidade](docs/Matriz_de_Rastreabilidade.xlsx) | Associação entre os 24 requisitos da matriz e os casos |
| 5. Consultar a execução | [Evidências](evidencias/) | Capturas organizadas por módulo e identificadas pelo caso |
| 6. Ler a consolidação | [Relatório Final](docs/%5BGURU%5D%20Relat%C3%B3rio%20Final%20de%20Testes.docx) | Ambiente e resultados registrados no ciclo |
| 7. Ver a organização | [Capturas do Jira](jira/) | Backlog, quadro Kanban e tarefa de execução |

Para examinar os documentos, baixe os arquivos Word e Excel e abra-os em um aplicativo compatível. Este repositório reúne artefatos de testes manuais; sua consulta não exige instalação de dependências nem execução de código.

## Escopo dos casos documentados

| Módulo | Cenários | Casos |
| --- | --- | --- |
| Cadastro | Cadastro válido, e-mail existente, campos ausentes, e-mail inválido e interrupção do cadastro | CT001 a CT006 (6) |
| Login, logout e conta | Credenciais válidas e inválidas, campos vazios, saída e exclusão de conta | CT007 a CT011 e CT042 (6) |
| Produtos | Listagem, detalhes, busca, categorias e marcas | CT012 a CT018 (7) |
| Carrinho | Adição, visualização, remoção e manutenção dos itens durante a navegação | CT019 a CT025 (7) |
| Checkout | Entrada com/sem autenticação, resumo, pagamento e confirmação | CT026 a CT031 (6) |
| Contato | Envio válido, campos vazios e anexo | CT032 a CT034 (3) |
| Newsletter | E-mail válido e campo vazio | CT035 a CT036 (2) |
| Avaliações | Envio válido e campos obrigatórios vazios | CT037 a CT038 (2) |
| Navegação | Páginas principais, menu Home e Scroll Up | CT039 a CT041 (3) |
| **Total** | | **42** |

Os casos incluem fluxos positivos, negativos e um fluxo alternativo, com prioridades registradas na planilha. O plano propõe técnicas como particionamento de equivalência e análise de valor limite; sua menção no planejamento não comprova, por si só, a aplicação de cada técnica a todos os casos.

## Resultados registrados

Os números abaixo descrevem o ciclo documentado na planilha e no relatório final. Não são o resultado de uma nova execução do site.

| Indicador | Registro |
| --- | ---: |
| Casos planejados | 42 |
| Casos executados | 42 |
| Casos com status “Passou” | 42 |
| Casos reprovados | 0 |
| Casos bloqueados | 0 |
| Requisitos com casos associados na matriz | 24 de 24 |
| Bugs identificados no relatório final | 0 |

**Como interpretar:** os 24 de 24 itens representam a vinculação de casos aos requisitos daquela matriz. Isso não comprova cobertura integral da ERS, do código-fonte, de todos os fluxos do site ou de todos os ambientes. Nenhum bug registrado nesse ciclo não significa ausência de defeitos.

## Pendências de consistência documental

A revisão dos artefatos identifica pontos a tratar em uma próxima atualização:

1. **ERS e matriz usam conjuntos diferentes:** a ERS descreve RF01 a RF27; a matriz e os casos utilizam RF001 a RF024. Há diferenças de conteúdo, além da numeração. Por exemplo, RF14 na ERS descreve remoção do carrinho; RF014 na matriz descreve visualização. É necessário reconciliar os requisitos e os vínculos antes de declarar cobertura integral da ERS.
2. **O cronograma do plano contém status antigos:** várias etapas aparecem como pendentes, embora os casos, as evidências e o relatório final estejam no repositório. O plano precisa refletir o fechamento do ciclo.
3. **Os documentos Word mantêm campos do modelo:** o histórico de revisões ainda contém “Seu Nome Completo”; a ficha técnica da ERS também apresenta erros de digitação no nome do autor.

Esses pontos são pendências dos documentos de origem. Este README preserva os resultados registrados, sem tratar a revisão do texto como correção dos artefatos ou nova validação funcional.

## Ambiente e limites

O relatório final registra **Google Chrome em Linux**, no ambiente web público, com evidências em PNG. Não informa a versão exata do navegador nem a resolução utilizada.

O pagamento foi avaliado como fluxo de demonstração, sem processamento financeiro real. As confirmações de contato, newsletter e avaliações pela interface não comprovam entrega de e-mails ou funcionamento de serviços externos.

Conforme o plano, ficaram fora do escopo:

- Automação, testes diretos de API, testes unitários e de integração.
- Desempenho, carga, stress e segurança.
- Acessibilidade e compatibilidade entre diversos navegadores e dispositivos.
- Instalação, recuperação de desastres e tolerância a falhas.

Os [cenários oficiais do site](https://automationexercise.com/test_cases) podem orientar ampliações. Os 42 casos deste projeto têm organização própria; não há um mapeamento que comprove a execução integral dos cenários oficiais.

## Processo e ferramentas

O trabalho reúne levantamento de requisitos, planejamento, elaboração de casos, rastreabilidade, execução manual, coleta de evidências e consolidação de resultados.

| Ferramenta | Uso documentado |
| --- | --- |
| Microsoft Word | ERS, plano e relatório final |
| Microsoft Excel | Casos de teste e matriz de rastreabilidade |
| Jira Software | Organização das atividades, registrada em capturas |
| Automation Exercise | Aplicação sob teste |
| GitHub | Versionamento e apresentação dos artefatos |

## Evidências

As capturas estão em [evidencias/](evidencias/), separadas por módulo. Exemplos:

- [CT001: cadastro com dados válidos](evidencias/cadastro/CT001.png).
- [CT008: login com senha incorreta](evidencias/login/CT008.png).
- [CT029: finalização da compra](evidencias/checkout/CT029.png).
- [CT041: Scroll Up](evidencias/navegacao/CT0041.png), cujo nome de arquivo contém um zero adicional.

Uma captura apoia o registro da execução, mas não comprova isoladamente todos os passos e resultados do caso. A análise deve combinar caso de teste, status registrado e evidência.

## Estrutura do repositório

```text
docs/         # ERS, plano, relatório final, casos e matrizes
evidencias/   # Capturas por módulo e caso de teste
jira/         # Backlog, Kanban e tarefa de execução
README.md
```

## Continuidade

A próxima etapa documental é alinhar ERS, matriz e casos, atualizar o cronograma e os campos do modelo e recalcular a cobertura sobre o conjunto reconciliado.

O portfólio também possui um projeto de [automação com Cypress e Cucumber](https://github.com/Jefferson-Andrade/Automacao-Web-com-Cypress). Ele é uma suíte separada, com escopo próprio; não representa a automação integral dos 42 casos deste repositório.

Outras ampliações possíveis incluem testes de API, novos ambientes e cenários, desde que acompanhados de critérios, execução e evidências correspondentes.

## Autor

**Jefferson Andrade Coelho**  
Estudante de Análise e Desenvolvimento de Sistemas na UNINTER.
