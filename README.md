# SmartSplit

An AI-powered expense sharing platform that turns receipt photos into split, categorized expenses — and minimizes how many payments groups have to settle.

## Overview

SmartSplit combines OCR + Claude API to automatically extract line items from receipts, categorize transactions, and split them across group members. A graph-based optimization engine then computes the minimum number of settlements needed to clear debts, even with concurrent group updates.

## Features

- 📸 **Receipt OCR** — Extracts line items, totals, and vendor info from uploaded receipts
- 🧠 **AI categorization** — Claude API classifies transactions and suggests splits
- 🔗 **Settlement optimization** — Graph algorithm minimizes inter-user payments
- 🔁 **Idempotent APIs** — Safe retries for reliable expense tracking
- 👥 **Concurrent group updates** — Handles simultaneous edits without conflicts
- 📱 **Mobile-first** — React Native client for iOS and Android

## Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** TypeScript, React Native
- **AI:** Claude API
- **OCR:** Receipt parsing pipeline
- **Database:** PostgreSQL
