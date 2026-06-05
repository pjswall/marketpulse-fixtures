# DecisionWise SignalOps Fixtures

Static clean-signal and synthetic threat-fixture pages for the MarketPulse Shield / DecisionWise hackathon demo.

## What this repo contains

- `public/clean/` — benign fictional business-signal pages.
- `public/threats/` — safe synthetic red-team fixture pages and JSON files.
- `public/data/` — source metadata, company signals, event signals, and expected detections.
- `public/assets/style.css` — simple styling for the static pages.

All companies and claims are fictional. The threat pages are clearly marked as synthetic fixtures and are designed for crawler, Shield, Critic, and DecisionWise testing.

## Azure Static Web Apps configuration

When creating the Static Web App in Azure:

- Build preset: `Custom`
- App location: `/public`
- API location: leave blank
- Output location: leave blank

## Example routes

- `/clean/bharatmobility-supply-chain.html`
- `/threats/t01-prompt-injection.html`
- `/threats/t02-fake-press-release.html`
- `/data/company_signals.json`
- `/data/source_metadata.json`

## Safety note

These fixtures do not contain malware, phishing flows, credential collection, exploits, or real-world allegations. They are benign synthetic pages for testing agentic data-security and trust-governance behavior.

## Demo principle

DecisionWise does not only cite sources. It cites execution: where evidence came from, which agent processed it, what Shield blocked or downgraded, and why the final action was accepted or changed.
