# A/B Test Sample Size Calculator

Calculate the exact sample size and duration for statistically significant A/B test results.

**[Live Demo →](#)** *(add your GitHub Pages URL after deploying)*

## Screenshot

![screenshot](screenshot.png)

## What It Does

Input your baseline conversion rate, minimum detectable effect, daily traffic, significance level, and statistical power — the calculator shows:
- **Required sample size** per variation
- **Test duration** in days
- **Power curve chart** showing how statistical power grows over time
- **Full test details** breakdown

## How the Math Works

Uses the standard two-proportion z-test formula:
- Normal CDF approximation (Abramowitz & Stegun)
- Inverse normal CDF (rational approximation)
- Two-tailed test with configurable α and β

## Built With

- HTML, CSS, JavaScript (no framework)
- Chart.js for the power curve visualization
- JetBrains Mono for the monospaced metrics

## Why I Built This

As a PM, I've run dozens of A/B tests and seen teams either end tests too early (false positives) or run them too long (wasted time). This tool makes the math accessible so teams can plan experiments properly before they start.

## Author

**Prithvi** — [Portfolio](#)
