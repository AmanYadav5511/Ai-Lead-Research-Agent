# AI Market Expansion Research Agent

Automatically researches B2B leads and detects market 
expansion signals in 30 seconds.

## What it does
- Scrapes company website automatically
- Extracts expansion signals (new markets, funding, products)
- Scores buying intent 1-10 using GPT-4o model
- Writes personalized cold email opener
- Populates everything into Google Sheets

## Stack
n8n · OpenAI GPT-4o · Google Sheets

## How to use
1. Import the workflow JSON into n8n
2. Connect your Google Sheets + OpenAI credentials
3. Add company name + website to the sheet
4. Watch it run automatically.

NOTE - You have to enter company name(optional) and website first into google sheet and ai will do the rest.
