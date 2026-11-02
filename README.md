# Lucien Andrieux — AI Agents & Automation

Freelance since 2019 · n8n · APIs · Supabase · Google Sheets / Excel

I help companies automate their processes with AI, starting from where their data actually lives: Google Sheets, Excel, SharePoint.

AI where it truly adds value, code where the rule is strict, and people stay in control of the source data.

## Featured project

### [Spare Parts Anomaly Detector](https://github.com/LucienAndrieux/SparePartsAnomalyDetector)

An AI agent that detects data-entry anomalies every night in a spare-parts order tracking file.

- **n8n workflow** that only analyzes the rows changed in the Google Sheet
- **LLM** detection, with output validated in the workflow and enforced by database constraints
- **Supabase** (PostgreSQL, column-level Row Level Security) to store anomalies
- **React + Express dashboard**, with views by job and by owner
- **Verified resolution**: an anomaly is closed only after the row is re-checked at the source

Live demo: [lucien-anomalies-showcase.duckdns.org](https://lucien-anomalies-showcase.duckdns.org)

Video walkthrough: [Vimeo](VIMEO-URL)
Capstone project of the Le Wagon AI Product Builder program (2026)

### Shiftsmith — shift scheduling with a constraint solver

Monthly scheduling for shift-based teams, built around a fictional 28-employee, 6-section hotel.

- **Rule validator**: every rule is checked on each change (11 h rest, 6 consecutive days max, monthly weekend off, couples, staffing min/max, eligibility), with a one-click "Fix" that adds no new error.
- **Solver**: OR-Tools CP-SAT generates a full month, or replans the rest of the current month changing as few cells as possible. On a November 2026 trial with a 7-day sick leave: optimal in 3–4.5 s, 1 error left in the rest of the month (11 in the published version).
- **LLM requests**: free text becomes typed operations (Structured Outputs), applied only after a manager approves them.
- Hour bank, PDF export, EN/FR/PT interface.

**Stack**: Next.js, TypeScript, PostgreSQL, FastAPI, OR-Tools, Docker Compose + Caddy.
[Live demo](https://shift-smith.duckdns.org/start) (no account, fictional data) · [Code](https://github.com/LucienAndrieux/shift-smith)
## Other projects

- **[Job Tracker](https://github.com/LucienAndrieux/schema-planner-buddy)**: React + TypeScript app connected to Supabase
- **Python bots** hosted on a VPS, built with Claude Code
- **Client work**: KPI reporting with Power Query / DAX for Andritz Metals France; business app and API integrations (Pennylane, Podio, Google Ads, Google Analytics) for Meilleure Copro

## Stack

| Area | Tools |
| --- | --- |
| AI & automation | n8n, OpenAI API, RAG, MCP, Claude Code |
| Backend & data | Supabase, PostgreSQL, Python, REST APIs, OR-Tools, FastAPI |
| Frontend | React, TypeScript, Vite |
| Spreadsheets & BI | Google Sheets, Apps Script, Excel, Power Query, Power BI, Power Automate |

## Get in touch

- [Malt profile](https://www.malt.fr/profile/lucienandrieux)
- [LinkedIn](https://www.linkedin.com/in/lucienandrieux)

Available for remote missions · French & English
