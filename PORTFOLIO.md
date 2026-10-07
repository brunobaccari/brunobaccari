# Portfólio técnico de QA

[Voltar ao perfil](README.md) · [English version](PORTFOLIO.en.md)

📄 Currículo: [Português (PDF)](https://brunobaccari.github.io/cv/Bruno_Baccari_QA_PTBR.pdf) · [English (PDF)](https://brunobaccari.github.io/cv/Bruno_Baccari_QA_EN.pdf)

Projetos para examinar cenários, decisões de automação e execução no CI. Cada repositório tem instruções em português e inglês. Os links de Actions levam às execuções, summaries e artifacts disponíveis conforme a retenção de cada workflow.

## Projetos

| Projeto | O que foi colocado à prova | Execuções |
| --- | --- | --- |
| [Karate · Contratos de catálogo](https://github.com/brunobaccari/karate-api-catalog) | Paginação, ordenação, filtros e projeção na API DummyJSON hospedada, com Java e Karate. PATCH/DELETE são simulados; nova consulta verifica a ausência de persistência. | [Actions](https://github.com/brunobaccari/karate-api-catalog/actions) |
| [Postman · Newman HTTP](https://github.com/brunobaccari/postman-newman-http-contracts) | Unicode, codificação, tipos JSON, status e autenticação no Postman Echo hospedado. Sem persistência ou carga. | [Actions](https://github.com/brunobaccari/postman-newman-http-contracts/actions) |
| [LangChain · Contratos de contexto](https://github.com/brunobaccari/langchain-grounding-tests) | Seleção de políticas vigentes, referências permitidas, abstenção e parsing estrito. Testes offline da cadeia; sem avaliação de modelo real. | [Actions](https://github.com/brunobaccari/langchain-grounding-tests/actions) |
| [Robot · Appium Android](https://github.com/brunobaccari/robot-appium-android-cart) | Quantidade, total, remoção, retomada do background e reinício do carrinho nativo. APK oficial Sauce Labs e emulador Android, com keywords no padrão dos projetos Robot anteriores. | [Actions](https://github.com/brunobaccari/robot-appium-android-cart/actions) |
| [Detox · Ciclo de vida React Native](https://github.com/brunobaccari/detox-react-native-lifecycle) | Estado da interface, background/retomada e reinício do processo no exemplo oficial Wix. Build release com JS empacotado; exemplo sem backend ou persistência durável. | [Actions](https://github.com/brunobaccari/detox-react-native-lifecycle/actions) |
| [Playwright · Acessibilidade](https://github.com/brunobaccari/playwright-accessibility) | Teclado, foco, labels e scans axe no formulário W3C. Controle negativo detecta defeitos conhecidos; resultados inconclusivos continuam exigindo revisão manual. | [Actions](https://github.com/brunobaccari/playwright-accessibility/actions) |
| [k6 · Performance](https://github.com/brunobaccari/k6-api-performance) | Smoke de nove requisições na QuickPizza: contrato, restrições, autenticação e limites de tempo. Amostra pequena, sem estimativa de capacidade ou SLA. | [Actions](https://github.com/brunobaccari/k6-api-performance/actions) |
| [Pact · Contratos](https://github.com/brunobaccari/pact-api-contracts) | Contratos do consumidor verificados contra Restful Booker hospedado; rejeição de tipo incompatível e limpeza dos dados próprios. Sem Broker ou gate de deployment do provedor. | [Actions](https://github.com/brunobaccari/pact-api-contracts/actions) |
| [CodeceptJS · Fluxos web](https://github.com/brunobaccari/codeceptjs-web-flows) | Formulários Selenium hospedados: Unicode, campos readonly/disabled, seleção, arquivo e mudanças assíncronas, com Playwright como helper. | [Actions](https://github.com/brunobaccari/codeceptjs-web-flows/actions) |
| [Espresso · Intents Android](https://github.com/brunobaccari/espresso-android-intents) | Intents, retorno/cancelamento de contato e estado após recriar uma Activity no exemplo oficial Android. Discagem interceptada, sem chamada real. | [Actions](https://github.com/brunobaccari/espresso-android-intents/actions) |
| [pytest · OpenRouter Evals](https://github.com/brunobaccari/pytest-openrouter-evals) | Contrato da resposta, fontes, abstenção, contexto, prompt injection e tratamento de 429. Testes do avaliador e chamadas reais ao provedor têm execuções separadas. | [Actions](https://github.com/brunobaccari/pytest-openrouter-evals/actions) |
| [Playwright · Checkout](https://github.com/brunobaccari/playwright-checkout-quality) | Compra, validação de dados e carrinho. Troca de produto após cancelar a revisão exige recálculo dos itens, subtotal, taxa e total. | [Actions](https://github.com/brunobaccari/playwright-checkout-quality/actions) |
| [Playwright · Frames e player](https://github.com/brunobaccari/playwright-embedded-integrations) | Isolamento entre iframes, recarga de contexto, navegação em frameset legado e áudio real de outra origem: iniciar, pausar, retomar e avançar. | [Actions](https://github.com/brunobaccari/playwright-embedded-integrations/actions) |
| [Cypress · Catálogo](https://github.com/brunobaccari/cypress-catalog-quality) | Conferência entre interface e API do ServeRest. Usuário comum não pode editar/excluir produto; o estado é consultado depois da tentativa. | [Actions](https://github.com/brunobaccari/cypress-catalog-quality/actions) |
| [pytest · API de reservas](https://github.com/brunobaccari/pytest-api-booking) | Criação, leitura, alteração, exclusão, persistência e autorização na API Restful Booker. | [Actions](https://github.com/brunobaccari/pytest-api-booking/actions) |
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
