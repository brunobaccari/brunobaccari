# Bruno Baccari

**Especialista em QA e automação de testes orientada a IA**

[English version](README.en.md)

Atuo com qualidade de software em aplicações web, mobile, APIs e sistemas com IA. Combino automação, análise de regras de negócio e visão de produto para investigar o que mudou, quais fluxos podem ser afetados e que evidências sustentam uma entrega.

Este portfólio reúne minhas frentes de atuação e exemplos públicos de código para avaliação técnica.

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

## Projetos públicos

### [Playwright · TypeScript · Checkout](https://github.com/brunobaccari/playwright-checkout-quality)

Testes de checkout com aplicação local, conferindo quantidade, cupom e total na API e na interface. Inclui cenários de erro, entradas inválidas e execução no GitHub Actions.

**Para avaliar:** expectativas explícitas de cálculo, espera pela resposta da operação e evidências de falha. Os [14 cenários](https://github.com/brunobaccari/playwright-checkout-quality/blob/main/tests/checkout.spec.ts) evoluem a frente de checkout do projeto anterior com Selenium.

### [Cypress · ServeRest](https://github.com/brunobaccari/cypress-serverest)

Exemplo de organização de testes de frontend e API em JavaScript, com cenários de login, usuários e produtos, fixtures e comandos compartilhados.

**Para avaliar:** separação entre as camadas e verificações de resposta da API. O [cenário de produtos](https://github.com/brunobaccari/cypress-serverest/blob/HEAD/cypress/e2e/api/produtos.api.cy.js) inclui listagem, criação e exclusão.

### [Robot Framework · Appium · Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo)

Estrutura de automação mobile com Robot Framework e Appium, organizada em páginas, recursos, helpers e keywords.

**Para avaliar:** organização dos componentes e composição do [fluxo de login](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo/blob/HEAD/src/Appium/TestCases/Home.robot).

### [Python · Selenium · Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation)

Script de automação de uma jornada de login, carrinho e checkout, com captura de telas e logs.

**Para avaliar:** interação com a interface e registro das etapas no [script principal](https://github.com/brunobaccari/selenium-test-checkout-automation/blob/HEAD/arquivo_principal.py).

Esses repositórios são demonstrações públicas de automação. As skills e soluções desenvolvidas internamente nas empresas não fazem parte deles.

## Stack

| Área | Ferramentas |
| --- | --- |
| Linguagens | Python, TypeScript, JavaScript, C# |
| Automação | Playwright, Robot Framework, Selenium, Cypress, Appium, Tricentis Tosca |
| APIs e dados | Postman, Swagger, PostgreSQL, Oracle SQL |
| CI/CD e ambientes | GitHub Actions, Azure DevOps, GitLab, Docker, Linux |
| Apoio com IA | Codex, Cursor, Antigravity |
| Gestão de testes e requisitos | Azure Test Plans, Qase, Jira, Confluence |
