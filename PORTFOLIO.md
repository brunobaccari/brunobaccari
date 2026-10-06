# Portfólio técnico de QA

[Voltar ao perfil](README.md) · [English version](PORTFOLIO.en.md)

Projetos para examinar cenários, decisões de automação e execução no CI. Cada repositório tem instruções em português e inglês. Os links de Actions levam às execuções, summaries e artifacts disponíveis conforme a retenção de cada workflow.

## Projetos

| Projeto | O que foi colocado à prova | Execuções |
| --- | --- | --- |
| [Python · OpenRouter Evals](https://github.com/brunobaccari/openrouter-free-evals) | Contrato da resposta, fontes, abstenção, contexto, prompt injection e tratamento de 429. Testes do avaliador e chamadas reais ao provedor têm execuções separadas. | [Actions](https://github.com/brunobaccari/openrouter-free-evals/actions) |
| [Playwright · Checkout](https://github.com/brunobaccari/playwright-checkout-quality) | Compra, validação de dados e carrinho. Troca de produto após cancelar a revisão exige recálculo dos itens, subtotal, taxa e total. | [Actions](https://github.com/brunobaccari/playwright-checkout-quality/actions) |
| [Playwright · Frames e player](https://github.com/brunobaccari/playwright-embedded-integrations) | Isolamento entre iframes, recarga de contexto, navegação em frameset legado e áudio real de outra origem: iniciar, pausar, retomar e avançar. | [Actions](https://github.com/brunobaccari/playwright-embedded-integrations/actions) |
| [Cypress · Catálogo](https://github.com/brunobaccari/cypress-catalog-quality) | Conferência entre interface e API do ServeRest. Usuário comum não pode editar/excluir produto; o estado é consultado depois da tentativa. | [Actions](https://github.com/brunobaccari/cypress-catalog-quality/actions) |
| [Python · API de reservas](https://github.com/brunobaccari/python-api-booking) | Criação, leitura, alteração, exclusão, persistência e autorização na API Restful Booker. | [Actions](https://github.com/brunobaccari/python-api-booking/actions) |
| [Maestro · Android](https://github.com/brunobaccari/maestro-android-checkout) | Jornada de compra, quantidades e casos negativos no My Demo App, com execução em emulador no CI. | [Actions](https://github.com/brunobaccari/maestro-android-checkout/actions) |
| [Java · WireMock](https://github.com/brunobaccari/java-wiremock-shipping) | Contrato de frete e comportamento do cliente diante de timeout, respostas inválidas e recuperação do serviço simulado. | [Actions](https://github.com/brunobaccari/java-wiremock-shipping/actions) |
| [Robot · Selenium](https://github.com/brunobaccari/robot-selenium-checkout) | Keywords de login, compra e carrinho; retomada do checkout após cancelar o formulário sem perder o produto. | [Actions](https://github.com/brunobaccari/robot-selenium-checkout/actions) |
| [Selenium · Python](https://github.com/brunobaccari/selenium-saucedemo-tests) | Catálogo, ordenação e detalhe de produto. Após logout, acesso direto ao catálogo, carrinho e etapas do checkout deve ser bloqueado. | [Actions](https://github.com/brunobaccari/selenium-saucedemo-tests/actions) |
| [Cypress · JavaScript](https://github.com/brunobaccari/serverest-cypress) | Testes de interface e API do ServeRest, com relatórios e vídeos no CI. | [Actions](https://github.com/brunobaccari/serverest-cypress/actions) |

## Como revisar

1. Leia o cenário e a expectativa: qual falha faria diferença para o usuário ou para a integração?
2. Confira preparação e limpeza dos dados, isolamento e esperas por estado.
3. Abra uma execução do Actions e compare o resultado com o relatório. Um artifact não substitui o status do teste; uma execução antiga não aprova uma mudança nova.
4. Consulte os limites no README antes de extrapolar o resultado para produção.

Os exemplos web usam sites hospedados de demonstração. WireMock virtualiza o serviço HTTP para controlar as falhas. Android roda em emulador. No projeto de IA, fixtures determinísticas verificam o avaliador; apenas a execução live consulta o provedor. Esses resultados cobrem o escopo declarado de cada projeto.

## Exemplos anteriores

- [Cypress / ServeRest](https://github.com/brunobaccari/cypress-serverest): interface e API em JavaScript.
- [Robot / Selenium](https://github.com/brunobaccari/robot-selenium-demo): login e checkout organizados em keywords.
- [Robot / Appium / Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo): estrutura de automação de login Android.
- [Selenium / Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation): script de jornada com captura de telas e logs.

Esses quatro repositórios têm README PT-BR/EN e workflows. Cypress, Robot/Selenium e Selenium executam cenários nos sites de demonstração. O Appium legado verifica somente configuração e dry run; não comprova execução em dispositivo. Código e soluções internas das empresas não são publicados aqui.
