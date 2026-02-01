# SwiftTranslator Playwright Automation (Option 1)

This repository automates Singlish → Sinhala UI test scenarios for https://www.swifttranslator.com/.

## Prerequisites
- Node.js (LTS)

## Install
```bash
npm install
```

## Run tests
```bash
npx playwright test
```

## View HTML report
```bash
npx playwright show-report
```

## Notes
- Tests verify real-time output behavior (no Convert button).
- If strict matching fails due to minor spacing differences, change the assertion from `toBe` to `toContain` or a regex match.
