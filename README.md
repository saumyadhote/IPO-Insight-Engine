# IPO Insight Engine

An AI-powered dashboard that analyzes upcoming Indian IPOs and surfaces whether the fundamentals look strong.

## What it does

- Parses **SEBI DRHP filings** (public PDFs) to extract financials, risk factors, and business details
- Pulls **live GMP (Grey Market Premium)** data to gauge street sentiment
- Tracks **subscription numbers** (QIB, NII, retail) as they update
- Runs AI analysis to give you a plain-English take on each IPO's fundamentals

## Stack

- **Frontend** — Next.js (App Router)
- **AI** — Claude API for DRHP parsing and fundamental analysis
- **Data** — SEBI public filings + scraped GMP/subscription feeds

## Getting started

```bash
npm install
cp .env.example .env.local  # add your API keys
npm run dev
```

## Environment variables

| Variable | Description |
|---|---|
| `ANTHROPIC_API_KEY` | Claude API key for AI analysis |

## License

MIT
