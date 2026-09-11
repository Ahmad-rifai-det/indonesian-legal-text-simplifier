# ⚖️ Indonesian Legal Text Simplifier

An AI-powered tool built on the Claude API that translates dense Indonesian legal articles, court rulings, and documents into plain, easy-to-understand language — built as a portfolio project for **Claude Campus Ambassador (Builder Club track)**.

## Why this project exists

As a Business Law student, I often spent a lot of time trying to understand articles and rulings written in dense legal language. I started using Claude to help break those texts down into everyday language — and this project automates that habit, so other students (especially those outside law) can understand legal text without having to ask anyone.

## Features

* **Live Analysis** — paste any article or ruling and get a real-time result from the Claude API.
* **Model Choice** — pick between Sonnet 5 or Haiku 4.5, depending on your need for speed vs. depth of analysis.
* **Demo Mode (no API key needed)** — for a quick try without an API key, includes a real (not hand-written) example analysis of Article 1365 of the Indonesian Civil Code.
* **3-Tab Output** — Plain Summary, Glossary of Terms, and Impact & Implications.
* **Export Results** — download the analysis as a `.txt` file.

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

Enter your own Claude API key in the sidebar (get one at [console.anthropic.com](https://console.anthropic.com)), or click **"Run Demo Mode"** to see a sample result without needing an API key.

## Built With

* [Streamlit](https://streamlit.io) — web interface
* [Claude API](https://www.anthropic.com) (Anthropic) — legal text analysis

## Notes

This project was built within a limited timeframe as a technical exploration for the Claude Campus Ambassador application, by a Business Law student (Universitas Negeri Makassar) considering a transition into AI/engineering. Planned next step: support for uploading full PDF legal documents instead of only pasted text.

