# SARURA AgriForesight Rwanda

Prototype for NISR Big Data Hackathon 2026 — Track 1: Agricultural Productivity.

## Run locally
Open `index.html` in a browser. No installation or API key is required.

## Deploy with GitHub Pages
1. Create a public GitHub repository named `sarura-agriforesight-rwanda`.
2. Upload `index.html`, the `data/` folder, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, then Save.
6. After GitHub Pages publishes the site, copy the URL shown in Settings → Pages. That is the Deployed Web/App URL.

## Important data note
The supplied `poverty-status-among-agr.xls` file is an HTML table export, despite its `.xls` extension. It contains the poverty-status percentages reproduced in the dashboard. The Agriculture Household Survey 2024 PDF supplied with the project is documentation/metadata, not the underlying respondent-level microdata. Therefore this prototype does not claim to calculate crop yields, predict harvests, or produce market-risk scores yet.

## Included data
`data/poverty_status_agricultural_households.csv` contains the exact supplied figures:
- Poor: Rwanda 25.9%, Urban 27.0%, Rural 25.7%
- Non-poor: Rwanda 74.1%, Urban 73.1%, Rural 74.3%
