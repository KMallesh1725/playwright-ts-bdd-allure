# Playwright TypeScript BDD Allure Framework

## Features
- E2E Testing with Playwright
- BDD with Cucumber (Gherkin syntax)
- TypeScript for type safety
- Allure reporting

## Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Run BDD tests**
   ```bash
   npm run test
   ```

3. **Run Playwright UI tests**
   ```bash
   npm run test:ui
   ```

4. **Generate Allure Report**
   ```bash
   allure generate reports --clean -o allure-report
   allure open allure-report
   ```

## Folder Structure
- `features/` - Gherkin feature files & step definitions
- `tests/` - Playwright test scripts (optional, for pure Playwright)
- `reports/` - Output for Cucumber/Allure reports

## Customization
- Update `playwright.config.ts` and `cucumber.js` for your needs.
- Add more features and step definitions in `features/`.

## Allure Integration
- Allure reporting is enabled in the configuration. Use the commands above to view reports.