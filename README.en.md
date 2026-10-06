# Bruno Baccari

**QA Specialist · AI-assisted test automation**

[Versão em português](README.md)

I work with software quality across web applications, mobile apps, APIs and AI systems. I combine automation, business rule analysis and product experience to investigate what changed, which flows may be affected and what evidence supports a release.

This portfolio presents my areas of work and public code examples for technical review.

## Code and results

| Project | What to review | Verified run |
| --- | --- | --- |
| [Python · OpenRouter](https://github.com/brunobaccari/openrouter-free-evals) | JSON contracts, facts, sources and abstention; per-rule and per-response summaries. | [29 evaluator tests](https://github.com/brunobaccari/openrouter-free-evals/actions/runs/37477844991) |
| [Playwright · TypeScript](https://github.com/brunobaccari/playwright-checkout-quality) | SauceDemo checkout, totals, cart behavior and form validation. | [5/5](https://github.com/brunobaccari/playwright-checkout-quality/actions/runs/37475897115) |
| [Cypress · TypeScript](https://github.com/brunobaccari/cypress-catalog-quality) | ServeRest catalog, UI/API cross-checks and scenario-owned data. | [8/8](https://github.com/brunobaccari/cypress-catalog-quality/actions/runs/37475919215) |
| [Python · pytest](https://github.com/brunobaccari/python-api-booking) | CRUD, persistence and authorization against the Restful Booker API. | [8/8](https://github.com/brunobaccari/python-api-booking/actions/runs/37476153333) |
| [Maestro · Android](https://github.com/brunobaccari/maestro-android-checkout) | My Demo App checkout, quantities and negative cases; emulator-based CI. | [5/5](https://github.com/brunobaccari/maestro-android-checkout/actions/runs/37475734008) |
| [Java · WireMock](https://github.com/brunobaccari/java-wiremock-shipping) | Shipping contracts, timeouts, invalid responses and service recovery. | [16/16](https://github.com/brunobaccari/java-wiremock-shipping/actions/runs/37475753840) |
| [Robot Framework · Selenium](https://github.com/brunobaccari/robot-selenium-checkout) | Keyword-based checkout, totals and order confirmation. | [4/4](https://github.com/brunobaccari/robot-selenium-checkout/actions/runs/37480126480) |
| [Selenium · Python](https://github.com/brunobaccari/selenium-saucedemo-tests) | Sorting, product details, cart behavior and logout. | [6/6](https://github.com/brunobaccari/selenium-saucedemo-tests/actions/runs/37480244124) |
| [Cypress · JavaScript](https://github.com/brunobaccari/serverest-cypress) | API and frontend with Page Objects, JUnit and separate videos by layer. | [13/13](https://github.com/brunobaccari/serverest-cypress/actions/runs/37477540450) |

Runs verified on **October 6, 2026**. Links open the GitHub Actions **Summary**; **Artifacts** contain JUnit, HTML reports, screenshots or videos, depending on the suite. Downloads follow each workflow's retention period.

The [live model evaluation](https://github.com/brunobaccari/openrouter-free-evals/actions/runs/37477898147) passed all five cases, with zero cost reported by the API. Its summary shows the question, context, expected values, received response and each rule's result. The 29 tests in the table verify the evaluator; this small corpus is not a general assessment of model quality.

Projects include **Portuguese and English** documentation, reproduction commands and coverage limits. New projects record execution evidence in [Actions runs and artifacts](https://github.com/brunobaccari/brunobaccari/actions), including investigated failures. Android tests ran on an emulator; exploratory and Xray-import material is prepared but has not been executed in a tenant.

### Earlier projects

- [Cypress / ServeRest](https://github.com/brunobaccari/cypress-serverest): JavaScript UI and API tests.
- [Robot / Selenium](https://github.com/brunobaccari/robot-selenium-demo): keyword-based login and checkout.
- [Robot / Appium / Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo): Android login automation structure.
- [Selenium / Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation): a journey script with screenshots and logs.

These four examples also provide PT-BR/EN READMEs, but do not have a workflow. Internal company solutions are not part of this portfolio.

## What I can deliver

| Area | Deliverables |
| --- | --- |
| Test strategy | Risk analysis, business scenarios, acceptance criteria and regression coverage. |
| Web, mobile and API automation | Test suites, test data organization and reusable components for relevant product flows. |
| Delivery quality | CI/CD test integration, quality gates and execution records to support release decisions. |
| AI-assisted QA | QA skills, project instructions and automation assisted by Codex, Cursor and Antigravity, with review and execution of generated tests. |
| AI application testing | Scenarios for evaluating conversational agents and LLM-based systems: context, consistency, unsupported answers and variable behavior. |
| Failure investigation | Defect reproduction, integration analysis and investigation of flaky tests involving data, timing and shared state. |

## Applied experience

- **Mouts:** QA and AI-assisted automation work, including supporting tools and internal QA skills.
- **Blis AI — previous experience:** conversational AI testing and automation, focusing on response consistency and non-deterministic behavior.
- **MB Labs:** a **50/50 split between QA and Product Owner responsibilities** on fintech and banking projects. Used ChatGPT and later tools such as Cursor and Antigravity at work.
- **BRK:** used GPT-3 to support test creation and other QA activities before adopting assistants integrated into IDEs and CLIs.

My product experience informs quality analysis: understanding the business problem, questioning incomplete criteria and checking the behavior a delivery needs to support.

## How I structure work with AI

1. **Define the expected behavior:** gather business rules, user stories and acceptance criteria; resolve conflicting information before generating tests.
2. **Read the complete change:** cross-check relevant backend, frontend and test diffs, including contracts and consumers.
3. **Prepare the agent's context:** organize rules, instructions and reusable skills in the workspace, consulting the relevant repositories.
4. **Review and execute:** examine generated scenarios and validate outcomes in the system, with steps and evidence another person can inspect.
5. **Investigate and record:** analyze failures and intermittent behavior; record learning with its source and context for later revalidation.

Using AI in QA and evaluating AI applications are distinct competencies. Generating a scenario does not establish its coverage; executing a test requires comparing the result against a valid rule.

## Stack

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, C# |
| Automation | Playwright, Robot Framework, Selenium, Cypress, Appium, Tricentis Tosca |
| APIs and data | Postman, Swagger, PostgreSQL, Oracle SQL |
| CI/CD and environments | GitHub Actions, Azure DevOps, GitLab, Docker, Linux |
| AI assistance | Codex, Cursor, Antigravity |
| Test and requirements management | Azure Test Plans, Qase, Jira, Confluence |

The projects above also use **Java, Maestro and WireMock**; Xray examples are part of the mobile test strategy.
