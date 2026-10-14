# Cooperative Finance Fundamentals

A free, modern educational website teaching the fundamentals of cooperative finance — credit unions, cooperative principles, capital structure, governance, and practical tools.

Inspired by clean educational sites like [statisticsfundamentals.com](https://statisticsfundamentals.com/).

## Features

- **Homepage** with hero, stats, resource cards, topic pills, and core concepts
- **Learn section** (navbar dropdown) categorizing:
  - 7 Cooperative Principles
  - What is Cooperative Finance?
  - Ownership & Governance
  - Capital Structure & Equity
  - Surplus & Patronage
  - Sources of Finance
  - Lending & Credit
  - Credit Unions vs Banks
  - Community Impact
- **Interactive Tools**:
  - Patronage Dividend Calculator (fully working)
  - Share Capital Planner, Loan Comparison, Savings Growth (placeholders ready for expansion)
- Clean, responsive UI with teal/navy professional finance aesthetic

## How to View

Open `index.html` in any modern browser, or serve the folder with any static file server.

```bash
# Example
npx serve .
```

## Structure

```
├── index.html          # Homepage
├── css/styles.css      # Full design system
├── js/main.js
├── learn/              # Educational pages
│   ├── principles.html # Full content
│   ├── what-is.html
│   ├── vs-banks.html
│   └── ... (others as placeholders ready for content)
└── tools/
    ├── patronage.html  # Working calculator
    └── ...
```

Built for learners, cooperative practitioners, and anyone wanting to understand member-owned finance.
