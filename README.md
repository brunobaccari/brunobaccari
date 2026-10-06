# Bruno Baccari

**Especialista em QA e automação de testes orientada a IA**

[English version](README.en.md)

Atuo com qualidade de software em aplicações web, mobile, APIs e sistemas com IA. Combino automação, análise de regras de negócio e visão de produto para investigar o que mudou, quais fluxos podem ser afetados e que evidências sustentam uma entrega.

Este portfólio reúne minhas frentes de atuação e exemplos públicos de código para avaliação técnica.

## Código e resultados

| Projeto | O que você encontra | Execução conferida |
| --- | --- | --- |
| [Python · OpenRouter](https://github.com/brunobaccari/openrouter-free-evals) | Contrato JSON, fatos, fontes e abstenção; resumo por regra e resposta. | [29 testes do avaliador](https://github.com/brunobaccari/openrouter-free-evals/actions/runs/37477844991) |
| [Playwright · TypeScript](https://github.com/brunobaccari/playwright-checkout-quality) | Checkout no SauceDemo, totais, carrinho e validações de formulário. | [5/5](https://github.com/brunobaccari/playwright-checkout-quality/actions/runs/37475897115) |
| [Cypress · TypeScript](https://github.com/brunobaccari/cypress-catalog-quality) | Catálogo no ServeRest, conferência UI/API e dados isolados por cenário. | [8/8](https://github.com/brunobaccari/cypress-catalog-quality/actions/runs/37475919215) |
| [Python · pytest](https://github.com/brunobaccari/python-api-booking) | CRUD, persistência e autorização na API Restful Booker. | [8/8](https://github.com/brunobaccari/python-api-booking/actions/runs/37476153333) |
| [Maestro · Android](https://github.com/brunobaccari/maestro-android-checkout) | Checkout, quantidade e cenários negativos no My Demo App; emulador no CI. | [5/5](https://github.com/brunobaccari/maestro-android-checkout/actions/runs/37475734008) |
| [Java · WireMock](https://github.com/brunobaccari/java-wiremock-shipping) | Contrato de frete, timeout, respostas inválidas e recuperação do serviço. | [16/16](https://github.com/brunobaccari/java-wiremock-shipping/actions/runs/37475753840) |
| [Robot Framework · Selenium](https://github.com/brunobaccari/robot-selenium-checkout) | Checkout por keywords, valores e confirmação do pedido. | [4/4](https://github.com/brunobaccari/robot-selenium-checkout/actions/runs/37480126480) |
| [Selenium · Python](https://github.com/brunobaccari/selenium-saucedemo-tests) | Ordenação, detalhe do produto, carrinho e encerramento de sessão. | [6/6](https://github.com/brunobaccari/selenium-saucedemo-tests/actions/runs/37480244124) |
| [Cypress · JavaScript](https://github.com/brunobaccari/serverest-cypress) | API e frontend com Page Objects, JUnit e vídeos por camada. | [13/13](https://github.com/brunobaccari/serverest-cypress/actions/runs/37477540450) |

Execuções conferidas em **6 de outubro de 2026**. Os links abrem o **Summary** do GitHub Actions; os **Artifacts** contêm JUnit, relatórios HTML, screenshots ou vídeos, conforme a suíte. Os downloads seguem a retenção de cada workflow.

Na [avaliação com modelo real](https://github.com/brunobaccari/openrouter-free-evals/actions/runs/37477898147), os cinco casos passaram e a API informou custo zero. O summary mostra pergunta, contexto, valores esperados, resposta recebida e resultado de cada regra. Os 29 testes da tabela verificam o avaliador; esse corpus pequeno não é uma avaliação geral da qualidade do modelo.

Os projetos têm documentação em **português e inglês**, comandos para reprodução e limites de cobertura. As evidências dos projetos novos ficam em [Execuções e artifacts no Actions](https://github.com/brunobaccari/brunobaccari/actions), incluindo falhas investigadas. Os testes Android foram executados em emulador; o material de exploração e importação Xray está preparado, mas não foi executado em um tenant.

### Projetos anteriores

- [Cypress / ServeRest](https://github.com/brunobaccari/cypress-serverest): testes de interface e API em JavaScript.
- [Robot / Selenium](https://github.com/brunobaccari/robot-selenium-demo): login e checkout organizados em keywords.
- [Robot / Appium / Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo): estrutura de automação do login Android.
- [Selenium / Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation): script de jornada com telas e logs.

Esses quatro exemplos também têm README PT-BR/EN, mas não possuem workflow. As soluções internas das empresas não fazem parte deste portfólio.

## O que posso entregar

| Frente | Entregáveis |
| --- | --- |
| Estratégia de testes | Análise de riscos, cenários de negócio, critérios de aceite e cobertura de regressão. |
| Automação web, mobile e API | Suítes de testes, organização de dados e componentes reutilizáveis para os fluxos relevantes do produto. |
| Qualidade na entrega | Integração de testes ao CI/CD, definição de quality gates e registros de execução para apoiar a decisão de release. |
| QA com apoio de IA | Skills de qualidade, instruções de projeto e automação assistida por Codex, Cursor e Antigravity, com revisão e execução dos testes gerados. |
| Testes de aplicações com IA | Cenários para avaliar agentes conversacionais e sistemas com LLMs: contexto, consistência, respostas sem fundamento e comportamento variável. |
| Investigação de falhas | Reprodução de defeitos, análise de integrações e investigação de flakiness envolvendo dados, tempo e estado compartilhado. |

## Experiência aplicada

- **Mouts:** atuação com QA e automação orientada a IA, incluindo uso de ferramentas de apoio e criação de skills internas de qualidade.
- **Blis AI — experiência anterior:** testes de sistemas de IA conversacional e automação, com atenção à consistência das respostas e ao comportamento não determinístico.
- **MB Labs:** atuação dividida entre **QA e Product Owner, 50% em cada frente**, em projetos de fintech e bancos. Uso de ChatGPT e, posteriormente, ferramentas como Cursor e Antigravity no trabalho.
- **BRK:** uso de GPT-3 como apoio à criação de testes e outras atividades de QA, antes da adoção de assistentes integrados a IDEs e CLIs.

A experiência de produto entra na análise de qualidade: entender o problema de negócio, questionar critérios incompletos e verificar o comportamento que a entrega precisa atender.

## Como estruturo o trabalho com IA

1. **Definir o esperado:** reunir regras de negócio, histórias de usuário e critérios de aceite; esclarecer divergências antes de gerar testes.
2. **Ler a mudança completa:** cruzar os diffs relevantes de backend, frontend e testes, considerando contratos e consumidores.
3. **Preparar o contexto do agente:** organizar regras, instruções e skills reutilizáveis no workspace, consultando os repositórios pertinentes.
4. **Revisar e executar:** conferir os cenários gerados e validar o resultado no sistema, com passos e evidências que outra pessoa consiga verificar.
5. **Investigar e registrar:** analisar falhas e intermitências; registrar aprendizados com fonte e contexto para revalidá-los quando forem reutilizados.

Uso de IA no processo de QA e avaliação de aplicações com IA são competências distintas. Gerar um cenário não comprova sua cobertura; executar um teste exige comparar o resultado com uma regra válida.

## Stack

| Área | Ferramentas |
| --- | --- |
| Linguagens | Python, TypeScript, JavaScript, C# |
| Automação | Playwright, Robot Framework, Selenium, Cypress, Appium, Tricentis Tosca |
| APIs e dados | Postman, Swagger, PostgreSQL, Oracle SQL |
| CI/CD e ambientes | GitHub Actions, Azure DevOps, GitLab, Docker, Linux |
| Apoio com IA | Codex, Cursor, Antigravity |
| Gestão de testes e requisitos | Azure Test Plans, Qase, Jira, Confluence |

Nos projetos acima também uso **Java, Maestro e WireMock**; os exemplos de Xray estão vinculados à estratégia de testes mobile.
