# Demo Series

- Python 3.10 is required for the examples in this series.

Tools used in this series:

- OpenAI GPT-4 API to extract structured data from various sources (PDF, text)
- SEC-API.io to access SEC filings and SEC data
- AlgoSeek to access historical intraday stock price data
- WRDS CRSP to access fundamental data of companies
- Airtable API to save structured data
- OpenAI ChatGPT frontend to improve academic writing

## Setup

Use `source ./venv/bin/activate` to activate the Python 3.10 virtual environment.

## OpenAI GPT-4 API: Extract Structured Data from Papers and Save to Airtable

> [Open Jupyter Notebook](./gpt-4-api-extract-data-from-papers/demo.ipynb)

## OpenAI GPT-4 API: Extract Structured Data from SEC Filings and Perform Stock Price Impact Analysis

## SEC-API.io and Other Use Cases

- Material event disclosures
  - 1.01 Entering into material agreement
  - Impact of the reasons behind executive change on stock price. Extracted from 8-K Item 5.02.
  - 4.02 Notice of non-reliance on previously issued financial statements
  - Impact of first bankruptcy proceeding notification on stock prices
- Insider trading impact on stock prices (buy and sell)
- IPO X-day returns & prospectus 424B4 Analysis - Risk factors, auditors, underwriters, legal counsel, language complexity, financials, etc. and X-first day returns
- Press release classification and X-day returns
  - Clinical study endpoint (not) met (Phase 1, 2, 3)
  - Private offering
  - Earnings guidance raise
  - Extraordinary divis
- IPO participation as disclosed in 13Fs and impact on stock price
- Impact of changes in fundamentals to X-day returns
- S-1/S-3 share issuance impact on returns
- Return patterns across ETFs (daily returns, monthly returns, November to April vs May to October returns, same weekday returns, etc.)
- 424B2 (Complex Financial Products) prospectus analysis
- Classify reasons for late filing notices (NT 10-K/10-Q) and analyze the impact of different classes on stock prices
- Find instances where auditors raise substantial doubt about a company's ability to continue as going concern
- Company valuation framework based on historical stock prices rather than CAPM, DCF, DDM, etc.

## ChatGPT: Improving Academic Writing with AI

## Miscelaneous

- Data Sources
- Running LLMs locally with Llama.cpp
