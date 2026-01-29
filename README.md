This is complete Playwright + TypeScript automation framework.
It includes:
- UI Autoamtion using POM
- API testing with schema validation
- Visual Regression checks
- Testing with static and dynamic data
- Environment setup using '.env', I have used this for credentials

Folder Structure

- src/api/ => API wrapper classes and schema
- src/data/ => Static test data
- src/fixtures/ => Custom Test fixtures (page objects)
- src/pages/ => POM classes for UI
- src/utils/ => Utility files (e.g. faker data generator)
- tests/ => All test cases (UI + API)
- .env => Environment Configuration and credentials
-  package.json => Project dependencies and test scripts
- tsconfig.json => TypeScript configuration
- playwright.config.ts => Playwright configuration
- readMe.md Project explanation

Tool & Libraries
- Playwright => UI + API Automation
- TypeScript => Strong typing and coding safety
- Fake.js => Creating dynamic random test data
- Zod => API Schema Validation
- Dotenv => Managing Environment variables

Setup Instruction
1. Unzip the project folder
2. Install dependencies - "npm install"

How to Run Tests
- npm run test (UI, It opens HTML test report for UI)
- npm run test-api (API, It opens HTML test report for API)
