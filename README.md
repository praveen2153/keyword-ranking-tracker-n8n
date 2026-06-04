# Keyword Ranking Tracker using n8n & Keyword.com

## Overview

This project automates keyword ranking tracking using n8n and Keyword.com API.

The workflow reads keywords from Google Sheets, retrieves their latest Google ranking from Keyword.com, and stores the results in a reporting sheet for SEO monitoring and analysis.

---

## Problem Statement

SEO teams often spend significant time manually checking keyword rankings and preparing reports.

This automation eliminates manual effort by automatically fetching ranking data and updating reports in real time.

---

## Solution

The workflow:

1. Reads keywords from Google Sheets.
2. Processes keywords one by one.
3. Fetches ranking data from Keyword.com API.
4. Extracts ranking position and ranking URL.
5. Stores results in an output Google Sheet.
6. Generates a historical ranking log for SEO analysis.

---

## Workflow Architecture

Google Sheets (Keywords)
        ↓
Split In Batches
        ↓
Keyword.com API
        ↓
Extract Ranking Data
        ↓
Google Sheets (Results)

---

## Technologies Used

- n8n
- Google Sheets
- Keyword.com API
- HTTP Request Node
- JavaScript
- SEO Analytics

---

## Features

- Automated keyword ranking monitoring
- Google Sheets integration
- Keyword.com API integration
- Historical ranking tracking
- Scheduled execution support
- Batch processing for large keyword lists

---

## Input Sheet Format

| Keywords |
|-----------|
| hyundai spare parts |
| hyundai mobis india |
| genuine hyundai parts |

---

## Output Sheet Format

| Keyword | Rank | URL | Date |
|----------|------|------|------|
| hyundai spare parts | 5 | example.com | 2025-07-09 |

---

## Benefits

- Eliminates manual ranking checks
- Faster SEO reporting
- Centralized ranking database
- Easy performance tracking
- Scalable for hundreds of keywords

---

## Future Enhancements

- Email reporting
- Slack notifications
- Looker Studio dashboard integration
- Competitor ranking analysis
- Rank trend visualization

---

## Author

Praveen Kumar
