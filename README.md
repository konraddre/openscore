# OpenScore

AI-powered credit decisioning platform based on PSD2 Open Banking.

## Overview

OpenScore transforms Open Banking transaction data into transparent credit scores (300-850). Every decision includes a feature-level reason breakdown, a plain-language explanation, and a tamper-evident audit record, built for automated-decision governance under PSD2, GDPR, and the EU AI Act.

## Features

- **PSD2 Open Banking integration** — ingests raw bank transaction data
- **CatBoost ML model** — calibrated, gradient-boosted scoring (not a black box)
- **SHAP explainability** — every decision attributed to income stability, expense volatility, savings ratio
- **Audit trail** — tamper-evident JSON records exportable for KNF / UODO compliance
- **Risk analyst panel** — borderline cases routed to human review

## Tech Stack

- Next.js / React (frontend)
- Python / CatBoost (ML model)
- Vercel (deployment)
- PSD2 / Open Banking APIs

## Live Demo

[openscore-demo.vercel.app](https://openscore-demo.vercel.app)

## Compliance

Built with PSD2 · GDPR · EU AI Act in mind.
