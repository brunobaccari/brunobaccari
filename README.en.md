# Bruno Baccari

**QA Specialist · AI-assisted test automation**

[Versão em português](README.md)

I work with software quality across web applications, mobile apps, APIs and AI systems. I combine automation, business rule analysis and product experience to investigate what changed, which flows may be affected and what evidence supports a release.

This portfolio presents my areas of work and public code examples for technical review.

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

## Public projects

### [Cypress · ServeRest](https://github.com/brunobaccari/cypress-serverest)

An example of frontend and API test organization in JavaScript, with login, user and product scenarios, fixtures and shared commands.

**What to review:** separation between test layers and API response assertions. The [product scenario](https://github.com/brunobaccari/cypress-serverest/blob/HEAD/cypress/e2e/api/produtos.api.cy.js) includes listing, creation and deletion.

### [Robot Framework · Appium · Flutter](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo)

A mobile automation structure using Robot Framework and Appium, organized into pages, resources, helpers and keywords.

**What to review:** component organization and composition of the [login flow](https://github.com/brunobaccari/RobotFramework-Appium-Flutter-Demo/blob/HEAD/src/Appium/TestCases/Home.robot).

### [Python · Selenium · Checkout](https://github.com/brunobaccari/selenium-test-checkout-automation)

A script automating login, cart and checkout interactions, with screenshots and logs.

**What to review:** UI interaction and step recording in the [main script](https://github.com/brunobaccari/selenium-test-checkout-automation/blob/HEAD/arquivo_principal.py).

These repositories are public automation demonstrations. Skills and solutions developed internally at companies are not included.

## Stack

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, C# |
| Automation | Playwright, Robot Framework, Selenium, Cypress, Appium, Tricentis Tosca |
| APIs and data | Postman, Swagger, PostgreSQL, Oracle SQL |
| CI/CD and environments | GitHub Actions, Azure DevOps, GitLab, Docker, Linux |
| AI assistance | Codex, Cursor, Antigravity |
| Test and requirements management | Azure Test Plans, Qase, Jira, Confluence |
