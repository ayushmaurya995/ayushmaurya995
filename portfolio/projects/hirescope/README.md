# HireScope — Job Market Intelligence Dashboard

A lightweight dashboard that explores job-role, salary, location and skill patterns using a transparent illustrative dataset.

## What it shows
- Sample openings and average annual salary
- Average salary by role
- Openings by location
- Most-mentioned skills
- Role/location filters with reset

## Run locally
Open `index.html` in a modern browser. The charts use Chart.js from its public CDN, so an internet connection is needed for chart rendering.

## Data
`data/jobs_sample.csv` contains **illustrative sample records** prepared for this portfolio project. These are not current job listings, not scraped vacancies and not verified market salary benchmarks. Salary values are annual INR examples.

## Calculations
- Sample openings = sum of openings in filtered rows
- Average salary = mean annual salary in filtered rows
- Skill mentions = count of sample rows containing each skill

## Files
- `index.html` — complete interactive dashboard
- `data/jobs_sample.csv` — sample data
- `assets/dashboard-preview.svg` — dashboard preview artwork

## Tech
HTML · CSS · JavaScript · Chart.js · CSV

## Interview explanation
“HireScope is a small market exploration dashboard. I structured sample job records by role, location, skill and annual salary, then used simple aggregations to compare the sample. It demonstrates how structured data can support career and hiring conversations.”

## Limitations
This is a static front-end demonstration. It does not scrape job boards, provide live vacancies, verify salary ranges, or forecast hiring demand.
