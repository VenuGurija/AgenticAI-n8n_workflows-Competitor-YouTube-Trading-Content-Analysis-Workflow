# Competitor YouTube Trading Content Analysis Workflow

## Overview
Analyzes competitor YouTube trading content and generates ad scripts.

## Setup Requirements
- Apify account with YouTube scraper task
- OpenRouter API key
- Google Sheets with two sheets: `competitors` and `raw_results`

## Configuration
1. Import workflow into n8n
2. Set credentials in Workflow Configuration node
3. Update Google Sheet ID in Read/Append nodes

## Workflow Steps
1. Reads competitor names from Google Sheets
2. Searches YouTube for their trading strategy videos
3. Scrapes video data via Apify
4. Stores results in Google Sheets
5. Picks best performing video
6. Analyzes with AI
7. Generates ad scripts
