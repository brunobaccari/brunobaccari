# QA technical portfolio

[Back to profile](README.en.md) · [Versão em português](PORTFOLIO.md)

Projects for inspecting scenarios, automation decisions and CI execution. Every repository has Portuguese and English instructions. Actions links lead to runs, summaries and artifacts available within each workflow's retention period.

## Projects

| Project | What is tested | Runs |
| --- | --- | --- |
| [pytest · OpenRouter Evals](https://github.com/brunobaccari/pytest-openrouter-evals) | Response contracts, sources, abstention, context, prompt injection and 429 handling. Evaluator tests and live provider calls run separately. | [Actions](https://github.com/brunobaccari/pytest-openrouter-evals/actions) |
| [Playwright · Checkout](https://github.com/brunobaccari/playwright-checkout-quality) | Purchase, customer validation and cart behavior. Replacing an item after cancelling review requires recalculated items, subtotal, tax and total. | [Actions](https://github.com/brunobaccari/playwright-checkout-quality/actions) |
| [Playwright · Frames and player](https://github.com/brunobaccari/playwright-embedded-integrations) | Iframe isolation, context reloads, legacy frameset navigation and real cross-origin audio: start, pause, resume and seek. | [Actions](https://github.com/brunobaccari/playwright-embedded-integrations/actions) |
| [Cypress · Catalog](https://github.com/brunobaccari/cypress-catalog-quality) | ServeRest UI/API cross-checks. A regular user must not update or delete a product; state is read again after the attempt. | [Actions](https://github.com/brunobaccari/cypress-catalog-quality/actions) |
| [pytest · Booking API](https://github.com/brunobaccari/pytest-api-booking) | Creation, reads, updates, deletion, persistence and authorization against the Restful Booker API. | [Actions](https://github.com/brunobaccari/pytest-api-booking/actions) |
| [Maestro · Android](https://github.com/brunobaccari/maestro-android-checkout) | Purchase flow, quantities and negative cases in My Demo App, running on an emulator in CI. | [Actions](https://github.com/brunobaccari/maestro-android-checkout/actions) |
| [Java · WireMock](https://github.com/brunobaccari/java-wiremock-shipping) | Shipping contracts and client behavior under timeouts, invalid responses and recovery of the simulated service. | [Actions](https://github.com/brunobaccari/java-wiremock-shipping/actions) |
| [Robot · Selenium](https://github.com/brunobaccari/robot-selenium-checkout) | Login, purchase and cart keywords; resuming checkout after cancelling the customer form without losing the item. | [Actions](https://github.com/brunobaccari/robot-selenium-checkout/actions) |
| [Selenium · Python](https://github.com/brunobaccari/selenium-saucedemo-tests) | Catalog, sorting and product details. After logout, direct access to the catalog, cart and checkout steps must be blocked. | [Actions](https://github.com/brunobaccari/selenium-saucedemo-tests/actions) |
| [Cypress · JavaScript](https://github.com/brunobaccari/serverest-cypress) | ServeRest UI and API tests, with reports and videos in CI. | [Actions](https://github.com/brunobaccari/serverest-cypress/actions) |

## How to review

1. Read the scenario and expectation: which failure would affect the user or the integration?
2. Inspect data setup and cleanup, isolation and state-based waits.
3. Open an Actions run and compare its result with the report. An artifact does not replace test status; an older run does not approve a new change.
4. Read the README's limits before applying the result to production.

Web examples use hosted demo sites. WireMock virtualizes the HTTP service to control faults. Android runs on an emulator. In the AI project, deterministic fixtures test the evaluator; only the live run calls the provider. Results cover each project's declared scope.

## Earlier examples

- [Cypress / ServeRest](https://github.com/brunobaccari/cypress-serverest): JavaScript UI and API tests.
- [Robot / Selenium](https://github.com/brunobaccari/robot-selenium-demo): keyword-based login and checkout.
- [Robot / Appium / Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo): Android login automation structure.
- [Selenium / Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation): a journey script with screenshots and logs.

These four repositories have PT-BR/EN READMEs and workflows. Cypress, Robot/Selenium and Selenium run scenarios against hosted demo sites. Legacy Appium checks configuration and a dry run only; it does not establish device execution. Internal company code and solutions are not published here.
