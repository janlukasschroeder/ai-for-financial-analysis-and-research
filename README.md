# AI for Financial Analysis & Research

## Use Cases

1. GPT-4 API: Extract Structured Data from Papers and Save to Airtable. [Open Jupyter Notebook.](./gpt-4-api-extract-data-from-papers/demo.ipynb)
2. GPT-4 API: Extract Structured Data from SEC Filings and Perform Stock Price Impact Analysis.
   - [Open Jupyter Notebook.](./gpt-4-api-extract-data-from-sec-filings/demo.ipynb)
   - [Background on Material Event Disclosures in SEC Form 8-K Filings.](./gpt-4-api-extract-data-from-sec-filings/8K-background.ipynb)
3. ChatGPT: Improve Academic Writing with AI. [Open Jupyter Notebook.](./chatgpt-improve-academic-writing/demo.ipynb)
4. Financial Data Visualization. [Open Jupyter Notebook](./financial-data-visualization/demo.ipynb)
5. SEC-API.io and Other Use Cases. [Open Jupyter Notebook](./sec-api.io-and-other-use-cases/demo.ipynb)
6. Books and Further Reading. [Open Jupyter Notebook](./books-and-further-reading/demo.ipynb)

**Tools used in this series:**

- [OpenAI GPT-4 API](https://platform.openai.com/docs/guides/text-generation) to extract structured data from various sources (PDF, text)
- [SEC-API.io](https://sec-api.io) to access SEC filings and SEC data
- [AlgoSeek](https://algoseek.com/) to access historical intraday stock price data
- [WRDS Compustat Daily Updates - Fundamentals Quarterly](https://wrds-www.wharton.upenn.edu/pages/get-data/compustat-capital-iq-standard-poors/compustat/north-america-daily/fundamentals-quarterly/) to access fundamental data of companies
- [Airtable](https://airtable.com/) to save structured data
- [OpenAI ChatGPT](https://chat.openai.com/) to improve academic writing

## Setup

Python 3.10 is required for the examples in this series. To run the Jupyter notebooks locally, follow these steps:

1. Clone the repository: `git clone URL_OF_THIS_REPO`
1. Create a virtual environment with Python 3.10 inside the repository folder: `python3.10 -m venv venv`
1. Activate the virtual environment: `source ./venv/bin/activate`
1. Install the required packages: `pip install -r requirements.txt`
