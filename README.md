# CyberTech Intelligence

A self-hosted n8n project that collects cybersecurity
and technology news and delivers a concise digest
through Telegram.

## Objectives

- Automate news collection.
- Filter and format useful articles.
- Deliver a readable Telegram digest.
- Learn workflow automation, APIs, data processing,
  and AI-assisted information analysis.

## Architecture

RSS sources -> n8n -> Processing -> Telegram

## Development status

- [ ] Local n8n environment
- [ ] First RSS source
- [ ] Telegram delivery
- [ ] Single-message digest
- [ ] Duplicate detection
- [ ] Scheduled execution
- [ ] AI relevance scoring
- [ ] AI-generated summaries

## Security

- Do not commit API keys or bot tokens.
- Inspect exported workflow files before committing.
- Keep the n8n editor accessible only locally
  during initial development.