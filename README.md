# Multi-Agent Stock Analysis System

## Overview

The **Multi-Agent Stock Analysis System** is an AI-powered financial analysis project built using Python, Phi Agent, Groq LLM, and Yahoo Finance.

It uses multiple specialized AI agents to identify company stock symbols and retrieve stock market information, company fundamentals, and analyst recommendations.

## Features

- Company name to stock symbol lookup
- Stock price retrieval
- Company fundamentals analysis
- Analyst recommendations
- Multi-agent collaboration
- Automatic retry mechanism
- Structured stock comparison summaries

## Technologies Used

- Python
- Phi Agent
- Groq LLM
- Yahoo Finance
- yfinance tools
- python-dotenv

## AI Agents

**1. Company Lookup Agent**

- Identifies stock symbols from company names.
- Supports Infosys, Tesla, Apple, Microsoft, Amazon, and Google.

**2. Stock Analysis Agent**

- Fetches stock prices.
- Retrieves company fundamentals.
- Collects analyst recommendations.

**3. Finance Team Agent**

- Coordinates the specialized agents.
- Combines company lookup and stock analysis.
- Generates comparison summaries.

## Installation

Clone the repository:

```bash
git clone https://github.com/PavanTorlapatiCodes/multi-agent-stock-analysis-system.git
cd multi-agent-stock-analysis-system
```

Install dependencies:

```bash
pip install phidata groq yfinance python-dotenv
```

## API Configuration

Create a `.env` file in the project directory:

```env
GROQ_API_KEY=your_groq_api_key
```

Never upload your `.env` file or API key to GitHub.

## Run the Project

```bash
python stock_analysis.py
```

## Example Query

```text
Compare stock data for Apple and Google.
```

## Project Structure

```text
multi-agent-stock-analysis-system/
│
├── stock_analysis.py
├── README.md
├── requirements.txt
└── .gitignore
```

## Disclaimer

This project is intended for educational and informational purposes only. Stock information and analyst recommendations are not financial advice.

## Author

Pavan Kumar Torlapati
